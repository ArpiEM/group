<template>
    <div>
        <table class="forumTableContainer">
            <tr>
                <th>Ценообразование в строительстве</th>
                <th>
                    <img src="@/assets/icons/themeIcon.svg">
                    <span>Темы</span>
                </th>
                 <th>
                    <img src="@/assets/icons/repliesIcon.svg">
                    <span>Ответы</span>
                </th>
                <th>
                    <img src="@/assets/icons/viewsIcon.svg">
                    <span>Просмотры</span> 
                </th>
            </tr>
            <tr>
                <td>
                 <div class="m-r-13">
                    <img src="@/assets/icons/themeNewMessageIcon.svg">
                </div>
                 <div class="m-b-30">
                    <div class="first-row">
                        <img class="m-r-13" src="@/assets/icons/stickyIcon.svg">
                        <span class="title" @click="GoToAnswersPage">Вопросы-ответы</span>
                        <span class="review">(просматривают: 21)</span>
                    </div>
                    <div class="lastVisit">
                        <span>Последнее от</span>
                        <span class="visitDitails">Владимира вчера в 06:31</span>
                    </div>
                 </div>
                </td>
                <td>34</td>
                <td>234</td>
                <td>547</td>
            </tr>
            <tr>
                <td>
                 <div class="m-r-13"> 
                    <img src="@/assets/icons/popularThemeIcon.svg">
                </div>
                 <div class="m-b-30">
                    <div class="first-row">
                        <img class="m-r-13" src="@/assets/icons/lockIcon.svg">
                        <span class="title">Подсчет объемов работ</span>
                    </div>
                    <div class="lastVisit">
                        <span>Последнее от</span>
                        <span class="visitDitails">Подсчет объемов работ</span>
                    </div>
                 </div>
                </td>
                <td>123</td>
                <td>343</td>
                <td>745</td>
            </tr>
            <tr>
                <td>
                 <div class="m-r-13">
                    <img src="@/assets/icons/themeNoMessageIcon.svg">
                 </div>
                 <div class="m-b-30">
                    <div class="first-row">
                        <span class="title"> Поправочные коэффициенты</span>
                    </div>
                    <div class="lastVisit">
                        <span>Последнее от</span>
                        <span class="visitDitails">Вячеслава вчера в 06:31</span>
                    </div>
                 </div>
                </td>
                <td>34</td>
                <td>234</td>
                <td>547</td>
            </tr>
            <tr>
                <td>
                 <div class="m-r-13">
                    <img src="@/assets/icons/privateThemeIcon.svg">
                 </div>
                 <div class="m-b-30">
                    <div class="first-row">
                      <img class="m-r-13"  src="@/assets/icons/lockIcon.svg">
                        <span class="title">Сводный сметный расчет, Лимитиров...</span> 
                    </div>
                    <div class="lastVisit">
                        <span>Последнее от</span>
                        <span class="visitDitails">Анны 1 июня в 13:31</span>
                    </div>
                 </div>
                </td>
                <td>123</td>
                <td>343</td>
                <td>745</td>
            </tr>
            <tr>
                <td>
                 <div class="m-r-13">
                    <img src="@/assets/icons/themeNoMessageIcon.svg">
                 </div>
                 <div class="m-b-30">
                    <div class="first-row">
                        <span class="title">Элементы сметы </span>
                    </div>
                    <div class="lastVisit">
                        <span>Последнее от</span>
                        <span class="visitDitails">Владимира вчера в 06:31</span>
                    </div>
                 </div>
                </td>
                <td>34</td>
                <td>234</td>
                <td>547</td>
            </tr>
            <tr>
                <td>
                 <div class="m-r-13">
                    <img src="@/assets/icons/themeNoMessageIcon.svg">
                 </div>
                 <div class="m-b-30">
                    <div class="first-row">
                      <img class="m-r-13" src="@/assets/icons/lockIcon.svg">
                        <span class="title">Методы расчета цены</span>
                    </div>
                    <div class="lastVisit">
                        <span>Последнее от</span>
                        <span class="visitDitails">Елены 1 июня в 06:31</span>
                    </div>
                 </div>
                </td>
                <td>123</td>
                <td>343</td>
                <td>745</td>
            </tr>
            <tr>
                <td>
                  <div class="m-r-13">
                    <img src="@/assets/icons/themeNoMessageIcon.svg">
                  </div>
                  <div class="m-b-30">
                    <div class="first-row">
                      <span class="title">Договор подряда </span>
                    </div>
                    <div class="lastVisit">
                      <span>Последнее от</span>
                      <span class="visitDitails">Вячеслава вчера в 06:31 </span>
                    </div>
                  </div>
                </td>
                <td>34</td>
                <td>234</td>
                <td>547</td>
            </tr>
        </table>
        <table class="forumTableContainer m-t-50">
            <tr>
                <th>Поиск расценок в ГЭСН, ФЕР, ТЕР и пр.</th>
                <th>
                    <img src="@/assets/icons/themeIcon.svg">
                    <span>Темы</span>
                </th>
                <th>
                    <img src="@/assets/icons/repliesIcon.svg">
                    <span>Ответы</span>
                </th>
                 <th>
                    <img src="@/assets/icons/viewsIcon.svg">
                    <span>Просмотры</span> 
                </th>
            </tr>
            <tr>
                <td>
                 <div class="m-r-13">
                    <img src="@/assets/icons/themeNoMessageIcon.svg">
                 </div>
                 <div class="m-b-30">
                    <div class="first-row">
                      <img class="m-r-13" src="@/assets/icons/stickyIcon.svg">
                        <span class="title">Общестроительные работы</span>
                        <span class="review">(просматривают: 21)</span>
                    </div>
                    <div class="lastVisit">
                        <span>Последнее от</span>
                        <span class="visitDitails">Владимира вчера в 06:31</span>
                    </div>
                 </div>
                </td>
                <td>34</td>
                <td>234</td>
                <td>547</td>
            </tr>
            <tr>
                <td>
                 <div class="m-r-13">
                    <img src="@/assets/icons/themeNoMessageIcon.svg">
                 </div>
                 <div class="m-b-30">
                    <div class="first-row">
                        <span class="title">Ремонтные работы</span>
                    </div>
                    <div class="lastVisit">
                        <span>Последнее от</span>
                        <span class="visitDitails">Подсчет объемов работ</span>
                    </div>
                 </div>
                </td>
                <td>123</td>
                <td>343</td>
                <td>745</td>
            </tr>
            <tr>
                <td>
                 <div class="m-r-13">
                   <img src="@/assets/icons/themeNoMessageIcon.svg">
                 </div>
                 <div class="m-b-30">
                    <div class="first-row">
                        <span class="title">Монтажные работы</span>
                    </div>
                    <div class="lastVisit">
                        <span>Последнее от</span>
                        <span class="visitDitails">Вячеслава вчера в 06:31</span>
                    </div>
                 </div>
                </td>
                <td>34</td>
                <td>234</td>
                <td>547</td>
            </tr>
            <tr>
                <td>
                 <div class="m-r-13">
                   <img src="@/assets/icons/themeNoMessageIcon.svg">
                 </div>
                 <div class="m-b-30">
                    <div class="first-row">
                        <span class="title">Электромонтажные работы</span> 
                    </div>
                    <div class="lastVisit">
                        <span>Последнее от</span>
                        <span class="visitDitails">Анны 1 июня в 13:31</span>
                    </div>
                 </div>
                </td>
                <td>123</td>
                <td>343</td>
                <td>745</td>
            </tr>
            <tr>
                <td>
                 <div class="m-r-13">
                   <img src="@/assets/icons/themeNoMessageIcon.svg">
                 </div>
                 <div class="m-b-30">
                    <div class="first-row">
                        <span class="title">Слаботочные системы</span>
                    </div>
                    <div class="lastVisit">
                        <span>Последнее от</span>
                        <span class="visitDitails">Владимира вчера в 06:31</span>
                    </div>
                 </div>
                </td>
                <td>34</td>
                <td>234</td>
                <td>547</td>
            </tr>
            <tr>
                <td>
                 <div class="m-r-13">
                   <img src="@/assets/icons/themeNoMessageIcon.svg">
                 </div>
                 <div class="m-b-30">
                    <div class="first-row">
                        <span class="title">Пусконаладочные работы</span>
                    </div>
                    <div class="lastVisit">
                        <span>Последнее от</span>
                        <span class="visitDitails">Елены 1 июня в 06:31</span>
                    </div>
                 </div>
                </td>
                <td>123</td>
                <td>343</td>
                <td>745</td>
            </tr>
            <tr>
                <td>
                 <div class="m-r-13">
                   <img src="@/assets/icons/themeNoMessageIcon.svg">
                 </div>
                 <div class="m-b-30">
                    <div class="first-row">
                        <span class="title">Проектные работы</span>
                    </div>
                    <div class="lastVisit">
                        <span>Последнее от</span>
                        <span class="visitDitails">Вячеслава вчера в 06:31 </span>
                    </div>
                 </div>
                </td>
                <td>34</td>
                <td>234</td>
                <td>547</td>
            </tr>
        </table>
        <div class="iconDescriptions">
            <div class="row">
                <div class="rowWidth align-center row">
                    <img src="@/assets/icons/themeNoMessageIcon.svg" class="m-r-5">
                    <span>Обычная тема, нет новых сообщений</span>
                </div>
                <div class="m-l-50 align-center row rowWidth">
                  <img src="@/assets/icons/popularThemeIcon.svg" class="m-r-5">
                    <span>Популярная тема</span>
                </div>
            </div>
            <div class="row">
                <div class="rowWidth align-center row">
                  <img src="@/assets/icons/themeNewMessageIcon.svg" class="m-r-5">
                    <span>Обычная тема, нет новых сообщений</span>
                </div>
                <div class="m-l-50 rowWidth align-center row">
                    <img src="@/assets/icons/privateThemeIcon.svg" class="m-r-5">
                    <span>Закрытая тема</span>
                </div>
            </div>
        </div>
        <div class="goToBeginingBtn">
            <span class="goToBeginingBtnText">Наверх</span>
            <img src="@/assets/icons/arrowUpIcon.svg">
        </div>
    </div>
</template>
<script lang="ts">
import Vue from 'vue';
export default Vue.extend({
   methods:{
       GoToAnswersPage(){
           this.$router.push('forum/answers');
        }
   }
})
</script>
<style lang="scss">

</style>
