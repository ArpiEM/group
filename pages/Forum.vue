<template>
  <div>
   <Header></Header>
    <div class="page-content">
      <SideBar />
      <div class="container">
        <div class="forumTextContainer" id="forumTextContainer_" v-if="showText">
            <div class="groupHeaderText">Это только временный текст в группах</div>
            <div class="groupDescription">Расскажем, как научиться, в сообщениях группы.</div>
        </div>     
        <NavBar/>
        <nuxt-child v-on:childToParent="setShowText"/>
      </div>
    </div> 
  </div>
</template>
<script lang="ts">
import Vue from 'vue';
export default Vue.extend({
data(){
  return{
    showText: true
  }
},
methods:{
  setShowText(value: boolean){
    this.showText = value
    console.log(value, "test")
  }
}  
})
</script>
