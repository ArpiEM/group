<!-- <template>
    <div>
        <div class="searchBoxContainer">
            <input class="searchInput" placeholder="Поиск"/>
            <img class="searchIcon" src="@/assets/icons/searchIcon.svg">
        </div>
        <ForumTable/>
    </div>
</template>
<script lang="ts">
import Vue from 'vue';
import NavBar from '@/components/NavBar.vue';
import ForumTable from '@/components/NavBarPages/Forum/ForumTable.vue'
export default Vue.extend({
    components: {
        NavBar,
        ForumTable
    }
})
</script> -->
<template>
    <div>
        <Header></Header>
        <div class="container">
            <SideBar />
            <div>
                <div class="forumTextContainer">
                    <div class="groupHeaderText">Это только временный текст в группах</div>
                    <div class="groupDescription">Расскажем, как научиться, в сообщениях группы.</div>
                </div>
                <NavBar/>
                <div>
                    <div class="searchBoxContainer">
                        <input class="searchInput" placeholder="Поиск"/>
                        <img class="searchIcon" src="@/assets/icons/searchIcon.svg">
                    </div>
                    <ForumTable/>
                </div>
            </div>
            <RightSection />
        </div>
    </div>
</template>
<script lang="ts">
import Vue from 'vue';
import Header from '../components/Header.vue';
import NavBar from '@/components/NavBar.vue';
import ForumTable from '@/components/NavBarPages/Forum/ForumTable.vue';
import SideBar from '../components/SideBar.vue';
import RightSection from '../components/NavBarPages/Forum/RightSection.vue';
import Forum from '../pages/Forum.vue';
export default Vue.extend({
    components: {
        NavBar,
        ForumTable,
        Header,
        SideBar,
        RightSection,
    }
})
</script>