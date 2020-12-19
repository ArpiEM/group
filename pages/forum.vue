<template>
  <div class="container">
    <div class="forumTextContainer" id="forumTextContainer_" v-if="showText">
      <div class="groupHeaderText">Это только временный текст в группах</div>
      <div class="groupDescription">Расскажем, как научиться, в сообщениях группы.</div>
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
    components: {
      Header,
      SideBar
    },
    data() {
      return {
        showText: true
      };
    },
    methods: {
      setShowText(value: boolean) {
        this.showText = value;
        console.log(value, "test");
      }
    }
  });
</script>
