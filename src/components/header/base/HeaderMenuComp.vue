<script>
    export default{
        name: 'HeaderMenuComp'
    }
</script>

<template>
    <div class="header-menu">
        <div class="header-about-button button-block">
            <button class="about-button type-button">About</button>
            <div class="button-underline"></div>
        </div>
        <div class="header-contact-button button-block">
            <button class="contact-button type-button">Contact</button>
            <div class="button-underline"></div>
        </div>
        <div class="header-home-button button-block">
            <button class="home-button type-button">Home</button>
            <div class="button-underline"></div>
        </div>
    </div>
</template>

<style scoped>
.header-menu{
  position: absolute;
  height: 96px;
  left: 40.16%;
  right: 40.16%;
  top: 0px;
}
.header-about-button{
  position: absolute;
  width: 48px;
  height: 24px;
  left: calc(50% - 48px/2 - 10px);
  top: calc(50% - 24px/2);
}
.header-contact-button{
  position: absolute;
  width: 64px;
  height: 24px;
  left: calc(50% - 64px/2 + 78px);
  top: calc(50% - 24px/2);
}
.header-home-button{
  position: absolute;
  width: 44px;
  height: 24px;
  left: calc(50% - 44px/2 - 88px);
  top: calc(50% - 24px/2);
}
.about-button{
  position: absolute;
width: 48px;
height: 24px;
left: calc(50% - 48px/2);
top: 0px;
}
.contact-button{
  position: absolute;
  width: 64px;
  height: 24px;
  left: calc(50% - 64px/2);
  top: 0px;
}
.home-button{
  position: absolute;
  width: 44px;
  height: 24px;
  left: calc(50% - 44px/2);
  top: 0px;
}
.button-block{
  font-family: 'Bai Jamjuree';
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;

  text-align: center;

  color: #161513;
}
.type-button{
  border: none;
}
.button-underline{
  position: absolute;
height: 1px;
left: 0%;
right: 0%;
top: 24px;

background: #131416;
border-radius: 0px;
}
</style>