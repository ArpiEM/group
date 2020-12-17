<template>
    <div>
        <div class="forumTextContainer">
            <div class="groupHeaderText">Это только временный текст в группах</div>
            <div class="groupDescription">Расскажем, как научиться, в сообщениях группы.</div>
        </div>
        <NavBar/>
        <div class="searchBoxContainer">
            <input class="searchInput" placeholder="Поиск"/>
        </div>
        <ForumTable/>
    </div>
</template>
<script lang="ts">
import Vue from 'vue';
import NavBar from '@/components/NavBar.vue';
import ForumTable from '@/pages/NavBarPages/Forum/ForumTable.vue'
export default Vue.extend({
    name: "Forum",
    components: {
        NavBar,
        ForumTable
    }
})
</script>
<style lang="scss" scoped>

</style>