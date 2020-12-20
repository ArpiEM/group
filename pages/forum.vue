<template>
  <div class="container">
    <div class="forumTextContainer" v-if="showText">
      <div class="groupHeaderText">Это только временный текст в группах</div>
      <div class="groupDescription">Расскажем, как научиться, в сообщениях группы.</div>
    </div>
    <div v-else class="squareSection">
      <div></div>
      <div></div>
      <div></div>
      <div></div>
    </div>
    <NavBar/>
    <nuxt-child/>
  </div>
</template>
<script lang="ts">
  import Vue from "vue";

  export default Vue.extend({
    asyncData({route}) {
      return {
        // showText: route.name === "forum"
        showText: true // TODO ask question about texts
      }
    },
    watchQuery: true,
    methods: {
    }
  });
</script>
