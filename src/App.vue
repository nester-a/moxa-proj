<template>
  <HeaderComp/>
  <TitleComp/>
</template>

<script>
import HeaderComp from './components/header/HeaderComp.vue'
import TitleComp from './components/title/TitleComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    TitleComp,
  }
}
</script>

<style>
@font-face{
  font-family: 'Bai Jamjuree';
  src: url(@/fonts/BaiJamjuree-Regular.ttf);
}
#app {
  position: relative;
  width: 1440px;
  height: 7382px;
  background: #F2F1EF;
  font-family: 'Bai Jamjuree';
}

</style>
