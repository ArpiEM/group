<template>
  <div class="container">
    <div class="forumTextContainer">
      <div class="groupHeaderText">Это только временный текст в группах</div>
      <div class="groupDescription">Расскажем, как научиться, в сообщениях группы.</div>
    </div>
    <NavBar/>
    <div class="row w-100 forumBody">
      <div class="w-100">
        <div class="searchBoxContainer">
          <input class="searchInput" placeholder="Поиск"/>
          <AddThemeBtn class="onlySmallDisplays"/>
        </div>
        <ForumTable/>
      </div>
      <RightSection/>
    </div>
  </div>
</template>
<script lang="ts">
  import Vue from "vue";
  import NavBar from "@/components/NavBar.vue";
  import ForumTable from "@/pages/NavBarPages/Forum/ForumTable.vue";
  import AddThemeBtn from "@/pages/NavBarPages/Forum/parts/AddThemeBtn";
  import RightSection from "@/pages/NavBarPages/Forum/RightSection.vue";

  export default Vue.extend({
    name: "Forum",
    components: {
      NavBar,
      ForumTable,
      RightSection,
      AddThemeBtn
    }
  });
</script>
<style lang="scss" scoped>

</style>
