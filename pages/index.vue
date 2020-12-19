<template>
  <div class="container">
    <div class="forumTextContainer">
      <div class="groupHeaderText">Это только временный текст в группах</div>
      <div class="groupDescription">Расскажем, как научиться, в сообщениях группы.</div>
    </div>
    <NavBar/>
  </div>
</template>
<script lang="ts">
    import Vue from 'vue';
    import Header from '../components/Header.vue';
    import SideBar from '../components/SideBar.vue';
    export default Vue.extend({
        components: {
            Header,
            SideBar,
        }
    })
</script>
