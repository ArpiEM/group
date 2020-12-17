<template>
    <div>
        <Header></Header>
        <div class="page-content">
          <SideBar />
          <Forum />
        </div>
    </div>
</template>
<script lang="ts">
    import Vue from 'vue';
    import Header from '../components/Header.vue';
    import SideBar from '../components/SideBar.vue';
    import Forum from '../pages/NavBarPages/Forum/Forum.vue';
    export default Vue.extend({
        components: {
            Header,
            SideBar,
            Forum
        }
    })
</script>
