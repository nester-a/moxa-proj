<script>
    export default{
        name: 'TitleGreetingButtonsComp'
    }
</script>

<template>
    <div class="greeting-buttons">
        <div class="button-block order-button">
          <button class="type-button got-project-button">Got a project?</button>
        </div>
        <div class="button-block contact-button">
          <button class="type-button lets-talk-button">Let's talk</button>
        </div>
    </div>
</template>

<style scoped>
.greeting-buttons{
  width:323px;
  position: absolute;
  height: 50px;
  left: 0%;
  right: 52.09%;
  top: calc(50% - 50px/2 + 152px);

  display: flex;
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
.contact-button{
  width:144px;
  height: 50px;
  left: 0%;
  right: 0%;
  top: 0px;

  
  border: 1px solid #161513;
  border-radius: 0px;

  text-align: center;
  
  box-sizing: border-box;
  display: flex;
  align-items: center;
}
.type-button{
  border: none;
}

.lets-talk-button{
  margin-left: auto;
  margin-right: auto;
}
.order-button{
  width:179px;
  box-sizing: border-box;

  height: 50px;
  left: 0%;
  right: 0%;
  top: 0px;

  background: #161513;
  border: 1px solid #161513;
  border-radius: 0px;

  text-align: center;
  
  box-sizing: border-box;
  display: flex;
  align-items: center;
}
.got-project-button{
  margin-left: auto;
  margin-right: auto;
  color: white;
  background: black;
}
</style>