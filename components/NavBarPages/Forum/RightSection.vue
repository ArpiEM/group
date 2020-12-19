<template>
    <div class="rightContainer">
        <div class="row">
          <AddThemeBtn/>
          <div class="configIcon">
            <img src="@/assets/icons/settingsIcon.svg">
          </div>
        </div>
        <div class="groupCard">
            <div class="cardHeader">Популярные темы</div>
            <div class="cardContent">
                <div class="m-t-30">
                    <img src="@/assets/icons/triangleRigthIcon.svg">
                    <span class="cardText">Смета на СМР при упрощёнке..</span>
                </div>
                <div class="m-t-15">
                    <img src="@/assets/icons/triangleRigthIcon.svg">
                    <span class="cardText">Как понизить сметную стоимост..</span>
                </div>
                <div class="m-t-15">
                    <img src="@/assets/icons/triangleRigthIcon.svg">
                    <span class="cardText">Смета к контракту</span>
                </div>
                <div class="m-t-15">
                    <img src="@/assets/icons/triangleRigthIcon.svg">
                    <span class="cardText">Расчет смет по объектам аналога..</span>
                </div>
                <div class="m-t-15">
                    <img src="@/assets/icons/triangleRigthIcon.svg">
                    <span class="cardText">Непредвиденные расходы-2%</span>
                </div>
            </div>
        </div>
        <div class="groupCard">
            <div class="cardHeader">Активные пользователи</div>
            <div class="cardContent">
                <div class="m-t-30 row">
                    <span class="userIndexNumber">1</span>
                    <div class="activeUsers"><span class="userName">Наталья Нафимова</span><span class="userNumber">(234)</span></div>
                </div>
                <div class="m-t-15 row">
                    <span class="userIndexNumber">2</span>
                    <div class="activeUsers"><span class="userName">Айдар Галиуллин</span><span class="userNumber">(23)</span></div>
                </div>
                <div class="m-t-15 row">
                    <span class="userIndexNumber">3</span>
                    <div class="activeUsers"><span class="userName">Виктория Соснова</span><span class="userNumber">(75)</span></div>
                </div>
                <div class="m-t-15 row">
                    <span class="userIndexNumber">4</span>
                    <div class="activeUsers"><span class="userName">Евгений Марьясов</span><span class="userNumber">(108)</span></div>
                </div>
                <div class="m-t-15 row">
                    <span class="userIndexNumber">5</span>
                    <div class="activeUsers"><span class="userName">Иван Сащенко</span><span class="userNumber">(1568)</span></div>
                </div>
            </div>
        </div>
        <div class="groupCard">
            <div class="cardHeader">Статистика форума</div>
            <div class="cardContent">
                <div class="m-t-30 row">
                    <img src="@/assets/icons/usersOnlineIcon.svg">
                    <span class="forumStatistic">Онлайн сейчас: </span><span class="forumStatisticCount">234</span>
                </div>
                <div class="m-t-15 row">
                    <img src="@/assets/icons/folderIcon.svg">
                    <span class="forumStatistic">Всего тем: </span><span class="forumStatisticCount">23</span>
                </div>
                <div class="m-t-15 row">
                    <img src="@/assets/icons/repliesConturIcon.svg">
                    <span class="forumStatistic">Ответов добавлено: </span><span class="forumStatisticCount">75</span>
                </div>
            </div>
        </div>
        <div class="groupCard">
            <div class="cardHeader">Статистика форума</div>
            <div class="socialIcons">
                <div class="m-t-30 row">
                    <img src="@/assets/icons/socialMedia/facebookIcon.svg">
                    <img src="@/assets/icons/socialMedia/twitterIcon.svg">
                    <img src="@/assets/icons/socialMedia/mailIcon.svg">
                    <img src="@/assets/icons/socialMedia/vkIcon.svg">
                    <img src="@/assets/icons/socialMedia/okIcon.svg">
                </div>
            </div>
        </div>
        
    </div>
</template>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    components: {}
})
</script>
<style lang="scss" scoped>
</style>
