<template>
  <div class="container">
    <div class="forumTextContainer">
      <div class="groupHeaderText">Это только временный текст в группах</div>
      <div class="groupDescription">Расскажем, как научиться, в сообщениях группы.</div>
    </div>
    <!--<div v-else class="squareSection">
      <div></div>
      <div></div>
      <div></div>
      <div></div>
    </div>-->
    <NavBar/>
    <div class="row w-100 forumBody">
      <nuxt-child/>
      <RightSection v-if="showRightSection"/>
    </div>
  </div>
</template>
<script lang="ts">
  import Vue from "vue";

  export default Vue.extend({
    asyncData({route}) {
      return {
        showRightSection: !route.path.includes("configurations")
      }
    },
    watchQuery: true,
    methods: {
    }
  });
</script>
