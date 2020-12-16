<template>
    <div>
        <div class="forumTextContainer">
            <div class="groupHeaderText">Это только временный текст в группах</div>
            <div class="groupDescription">Расскажем, как научиться, в сообщениях группы.</div>
        </div>
        <NavBar/>
    </div>
</template>
<script lang="ts">
import Vue from 'vue';
import NavBar from '@/components/NavBar.vue'
export default Vue.extend({
    components:{
        NavBar
    }
})
</script>
<style lang="scss" scoped>

</style>