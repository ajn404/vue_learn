<template>
  <div class="hello">
    vue生命周期
   <br/>
   <img src="https://ask.qcloudimg.com/http-save/devdocs/2nenjp4bnk.png" height="1000px">
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- 使用scoped属性保证该CSS样式仅用于本组件 -->
<style scoped>
.hello{
  top:0;
  bottom:0;
  position:fixed;
  overflow-y:scroll;
  background-color:#123456;
  color:white
}
</style>
