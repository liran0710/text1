<template>
  <div>
    <input id="chatbox" type="text">
    <input  id="button" type="button" value="发送">
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
#chatbox{
  width: 290px;
  height: 30px;
  background-color:white;
  position: fixed;
  left: 10px;
  bottom: 55px;
}
#button{
  width: 55px;
  height: 30px;
  color: whitesmoke;
  background-color:green;
  position: fixed;
  right: 10px;
  bottom: 55px;
  border-radius: 5px;
}
</style>