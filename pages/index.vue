<template>
    <div>
        <Header></Header>
        <div class="mainContent">
            <SideBar></SideBar>
            <Forum></Forum>
            <RightSection></RightSection>
        </div>
    </div>
</template>
<script lang="ts">
import Vue from 'vue';
import Header from '../components/Header.vue';
import SideBar from '../components/SideBar.vue';
import RightSection from '../pages/NavBarPages/Forum/RightSection.vue';
import Forum from '../pages/NavBarPages/Forum/Forum.vue';
export default Vue.extend({
    components: {
        Header,
        SideBar,
        RightSection,
        Forum
    }
})
</script>