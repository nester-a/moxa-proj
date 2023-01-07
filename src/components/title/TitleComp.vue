<script>
  import TitleGreetingComp from './base/TitleGreetingComp.vue'

  export default{
    name: 'TitleComp',
    components:{
      TitleGreetingComp,
    }
  }
</script>

<template>
<div class="main-title">
    <div class="title-image"/>
    <TitleGreetingComp />
  </div>
</template>

<style scoped>

.main-title{
  position: absolute;
  height: 562.5px;
  left: 5.56%;
  right: 5.56%;
  top: 136px;
}

.title-image{
  position: absolute;
  height: 563px;
  left: 56.09%;
  right: 0%;
  top: 0px;

  background: url(@/assets/tayler-photo.png);
  border-radius: 0px;
}
</style>