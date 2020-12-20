<template>
  <div class="container">
    <div class="forumTextContainer">
      <div class="groupHeaderText">Это только временный текст в группах</div>
      <div class="groupDescription">Расскажем, как научиться, в сообщениях группы.</div>
    </div>
    <NavBar/>
    <div class="row w-100 forumBody">
        <div class="w-100">
            <!--<div class="mobileTitle">
                Мусор|
            </div>-->
            <div class="searchBoxContainer">
                <SearchBox class="newsSearch"/>
                <AddThemeBtn class="hideOnMobile onlySmallDisplays"/>
            </div>
            <div class="newsCard m-t-30">
                <div class="m-l-30 m-t-30">
                    <div class="newsCardContextHeader">Вывоз <b>мусора</b> Пенза. Вывоз <b>мусора</b> в Пенза Газель, Зил, Камаз</div>
                    <div class="m-t-8 newsCardContextBody">... Вывоз <b>мусора</b> Пенза,вывоз <b>мусора</b> в Пензе Газель, Зил, Камаз. Вывоз строительного <b>мусора</b> по Пензе, вывоз строй <b>мусора</b> на свалку недорого.</div>
                </div>
                <div class="borderBottom m-b-18"></div>
                <div class="m-l-30 m-b-18">Форум сметчиков » Разное » <span class="activeStyle">Реклама</span></div>
            </div>
            <div class="newsCard m-t-30">
                <div class="m-l-30 m-t-30">
                    <div class="newsCardContextHeader"><b>Мусор</b></div>
                    <div class="m-t-8 newsCardContextBody">... эксплуатировавшемся длительное время, скопился бытовой <b>мусора</b> , его необходимо убрать и вывезти на свалку. Затраты по уборке бытового <b>мусора</b> не учтены нормами накладных расходов , указанные затраты должны ...</div>
                </div>
                <div class="borderBottom m-b-18"></div>
                <div class="m-l-30 m-b-18">Форум сметчиков » Ценообразование в строительстве » <span class="activeStyle">Вопросы-ответы</span></div>
            </div>
             <div class="newsCard m-t-30">
                <div class="m-l-30 m-t-30">
                    <div class="newsCardContextHeader">Вывоз <b>мусора</b> Пенза. Вывоз <b>мусора</b> в Пенза Газель, Зил, Камаз</div>
                    <div class="m-t-8 newsCardContextBody">... Вывоз <b>мусора</b> Пенза,вывоз <b>мусора</b> в Пензе Газель, Зил, Камаз. Вывоз строительного <b>мусора</b> по Пензе, вывоз строй <b>мусора</b> на свалку недорого.</div>
                </div>
                <div class="borderBottom m-b-18"></div>
                <div class="m-l-30 m-b-18">Форум сметчиков » Разное » <span class="activeStyle">Реклама</span></div>
            </div>
        </div>
        <RightSection/>
    </div>
  </div>
</template>
<script lang="ts">
  import Vue from "vue";

  export default Vue.extend({
  });
</script>
