<script>
  export default{
    name: 'HeaderLogoComp',
  }
</script>

<template>
    <div class="header-img">
        <div class="img-one">
            <img src="@/assets/moxa-img.png" alt="moxa-img">
        </div>
        <div class="img-two">
            <img src="@/assets/moxa.png" alt="moxa">
        </div>
    </div>
</template>

<style scoped>
.header-img{
  position: absolute;
  height: 32px;
  left: 0%;
  right: 89.77%;
  top: calc(50% - 32px/2);

  border-radius: 0px;
}
.img-one{
  position: absolute;
  left: 0%;
  right: 75.57%;
  top: 0%;
  bottom: 0%;
}
.img-two{
  position: absolute;
  left: 34.27%;
  right: 0.18%;
  top: 23.11%;
  bottom: 23.98%;
}
</style>