<template>
  <div class="hello">
    <div class="red">ndfgwe</div>
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

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.red{
  font-size: 30px;
  width:100%;
  background: red;
  height: 20px;
}
</style>
