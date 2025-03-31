<template>
<h1>Hello World!</h1>
<div class="logo">
  <img src="../assets/logo1.jpg" class="logo">
</div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h1 {
  color: rgba(41,52,57,100);
  font-size: 2em;
  font-weight: 400;
  margin-top: 20px;
  margin-bottom: 20px;
  text-align: center;
}

.logo{ 
  width: 100px;
  height: 100px;
  margin: 0 auto;
  display: block;
  margin-top: 20px;
  margin-bottom: 20px;
}
</style>
