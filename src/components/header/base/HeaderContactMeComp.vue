<script>
    export default{
        name: 'HeaderContactMeComp'
    }
</script>

<template>
    <div class="header-button button-block">
        <button class="lets-talk-button type-button">Let's talk</button>
    </div>
</template>

<style scoped>
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
.header-button{
  position: absolute;
  width: 126px;
  height: 42px;
  right: 0px;
  top: calc(50% - 42px/2);

  
  border: 1px solid #161513;
  border-radius: 0px;

  text-align: center;
  
  box-sizing: border-box;
  display: flex;
  align-items: center;
}
.lets-talk-button{
  margin-left: auto;
  margin-right: auto;
}
</style>