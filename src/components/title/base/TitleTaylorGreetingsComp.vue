<script>
    export default{
        name: 'TitleTaylorGreetingsComp'
    }
</script>

<template>
    <div class="greetings-from-tayler">
        <div>
          <span>HI, I'M TAYLER.</span>
        </div>
        <div>
          <span>A CREATIVE</span>
          <img class="medium-img" src="@/assets/moxa-img.png" alt="moxa-img">
          <span>DESIGNER</span>
        </div>
        <div>
          <span>BASED IN LONDON</span>
        </div>
    </div>
</template>

<style scoped>
.greetings-from-tayler{
  position: absolute;
height: 200px;
left: 0%;
right: 0%;
top: calc(50% - 200px/2 - 77px);

font-family: 'Bai Jamjuree';
font-style: normal;
font-weight: 400;
font-size: 56px;
line-height: 64px;
}

.medium-img{
  height: 40px;
  width: 40px;
  margin-left: 12px;
  margin-right: 12px;;
}
</style>