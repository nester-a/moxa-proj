<script>
  import TitleGreetingButtonsComp from './TitleGreetingButtonsComp.vue';
  import TitleGreetingMainSkillsComp from './TitleGreetingMainSkillsComp.vue';
  import TitleTaylorGreetingsComp from './TitleTaylorGreetingsComp.vue';

  export default{
    name: 'TitleGreetingComp',
    components:{
      TitleGreetingButtonsComp,
      TitleGreetingMainSkillsComp,
      TitleTaylorGreetingsComp,
    }
  }
</script>

<template>
    <div class="greeting">
      <TitleGreetingButtonsComp/>
      <TitleGreetingMainSkillsComp/>
      <TitleTaylorGreetingsComp/>
    </div>
</template>

<style scoped>

.greeting{
  position: absolute;
  height: 562.5px;
  left: 0%;
  right: 47.33%;
  top: 0px;
}
</style>