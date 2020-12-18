<template>
<div id="app">
  <h2 v-text="message"></h2>
  <h2 v-text="info"></h2>
</div>
</template>

<script>
export default {
name: "vue1"
}
var app =new vue({
  el :"#app",
  data: {
    message:"程序",
    info:"前端",
  }
})
</script>

<style scoped>

</style>
