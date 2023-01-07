<script>
 export default{
    name: 'TitlteGreetingMainSkillsComp'
 }
</script>

<template>
    <div class="main-skills">
        <div class="skill">
          <span>DESIGN</span>
        </div>
        <div class="small-img">
          <img class="small-img" src="@/assets/moxa-img.png" alt="moxa-img">
        </div>
        <div class="skill">
          <span>DEVELOPMENT</span>
        </div>
        <div class="small-img">
          <img class="small-img" src="@/assets/moxa-img.png" alt="moxa-img">
        </div>
        <div class="skill">
          <span>WEBFLOW</span>
        </div>
    </div>
</template>

<style scoped>
.main-skills{
  position: absolute;
  height: 32px;
  left: 0%;
  right: 29.91%;
  top: calc(50% - 32px/2 + 71px);

  display: flex;
  width: 472.5px;
  justify-content: space-between;
  align-items: center;
}
.small-img{
  height: 20px;
  width: 20px;
}
.skill{
left: 28.99%;
right: 35.03%;
top: calc(50% - 32px/2 - 0.25px);

font-family: 'Bai Jamjuree';
font-style: normal;
font-weight: 400;
font-size: 23px;
line-height: 32px;

letter-spacing: 0.48px;

color: #161513;
}

</style>