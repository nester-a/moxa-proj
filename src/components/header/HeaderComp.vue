<script>
  import HeaderLogoComp from './base/HeaderLogoComp.vue'
  import HeaderMenuComp from './base/HeaderMenuComp.vue'
  import HeaderContactMeComp from './base/HeaderContactMeComp.vue'

export default{
  name: 'HeaderComp',
  components:{
    HeaderLogoComp,
    HeaderMenuComp,
    HeaderContactMeComp,
  }
}
</script>

<template>
    <div class="header">
        <div class="header-block">
          <HeaderLogoComp/>
          <HeaderMenuComp/>
          <HeaderContactMeComp/>
        </div>
    </div>
</template>

<style scoped>
.header{
  position: absolute;
  width: 1440px;
  height: 96px;
  left: calc(50% - 1440px/2);
  top: 0px; 
}
.header-block{
  position: absolute;
  height: 96px;
  left: 5.56%;
  right: 5.56%;
  top: calc(50% - 96px/2);
}
</style>