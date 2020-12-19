<template>
  <div class="container">
    <div class="forumTextContainer" id="forumTextContainer_" v-if="showText">
      <div class="groupHeaderText">Это только временный текст в группах</div>
      <div class="groupDescription">Расскажем, как научиться, в сообщениях группы.</div>
    </div>
    <div v-else>
      en qarakusi anterner@
    </div>
    <NavBar/>
    <nuxt-child/>
  </div>
</template>
<script lang="ts">
  import Vue from "vue";
  import Header from "../components/Header.vue";
  import SideBar from "../components/SideBar.vue";

  export default Vue.extend({
    asyncData({route}) {
      return { showText: route.name === "forum" }
    },
    watchQuery: true,
    components: {
      Header,
      SideBar
    },
    methods: {
    }
  });
</script>
