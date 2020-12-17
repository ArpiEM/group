<template>
    <div class="rightContainer">
        <div class="row">
          <AddThemeBtn/>
          <div class="configIcon">icon</div>
        </div>
        <div class="groupCard">
            <div class="cardHeader">Популярные темы</div>
            <div class="cardContent">
                <div class="m-t-30">
                    <span>icon</span>
                    <span class="cardText">Смета на СМР при упрощёнке..</span>
                </div>
                <div class="m-t-15">
                    <span>icon</span>
                    <span class="cardText">Как понизить сметную стоимост..</span>
                </div>
                <div class="m-t-15">
                    <span>icon</span>
                    <span class="cardText">Смета к контракту</span>
                </div>
                <div class="m-t-15">
                    <span>icon</span>
                    <span class="cardText">Расчет смет по объектам аналога..</span>
                </div>
                <div class="m-t-15">
                    <span>icon</span>
                    <span class="cardText">Непредвиденные расходы-2%</span>
                </div>
            </div>
        </div>
        <div class="groupCard">
            <div class="cardHeader">Активные пользователи</div>
            <div class="cardContent">
                <div class="m-t-30 row">
                    <span class="userIndexNumber">1</span>
                    <span class="activeUsers">Наталья Нафимова  <span class="userNumber">(234)</span>

                    </span>
                </div>
                <div class="m-t-15 row">
                    <span class="userIndexNumber">2</span>
                    <span class="activeUsers">Айдар Галиуллин<span class="userNumber">(23)</span></span>
                </div>
                <div class="m-t-15 row">
                    <span class="userIndexNumber">3</span>
                    <span class="activeUsers">Виктория Соснова<span class="userNumber">(75)</span></span>
                </div>
                <div class="m-t-15 row">
                    <span class="userIndexNumber">4</span>
                    <span class="activeUsers">Евгений Марьясов <span class="userNumber">(108)</span></span>
                </div>
                <div class="m-t-15 row">
                    <span class="userIndexNumber">5</span>
                    <span class="activeUsers">Иван Сащенко <span class="userNumber">(1568)</span></span>
                </div>
            </div>
        </div>
        <div class="groupCard">
            <div class="cardHeader">Статистика форума</div>
            <div class="cardContent">
                <div class="m-t-30 row">
                    <span>icon</span>
                    <span class="forumStatistic">Онлайн сейчас: </span><span class="forumStatisticCount">234</span>
                </div>
                <div class="m-t-15 row">
                    <span>icon</span>
                    <span class="forumStatistic">Всего тем: </span><span class="forumStatisticCount">23</span>
                </div>
                <div class="m-t-15 row">
                    <span>icon</span>
                    <span class="forumStatistic">Ответов добавлено: </span><span class="forumStatisticCount">75</span>
                </div>
            </div>
        </div>
        <div class="groupCard">
            <div class="cardHeader">Статистика форума</div>
            <div class="cardContent">
                <div class="m-t-30 row">
                    <span>icon</span>
                    <span>icon</span>
                    <span>icon</span>
                    <span>icon</span>
                    <span>icon</span>
                </div>
            </div>
        </div>
        
    </div>
</template>
<script lang="ts">
import Vue from 'vue'
import AddThemeBtn from "@/pages/NavBarPages/Forum/parts/AddThemeBtn";
export default Vue.extend({
    components: {
      AddThemeBtn
    }
})
</script>
<style lang="scss" scoped>
</style>
