<template>
  <div id="container">
    <h1>{{ initData }}</h1>
  </div>
</template>
<script>
import $ from 'jquery';
export default {
  data() {
    return {
      initData: "vue开发环境运行成功~~~"
    };
  },
  created() {
    console.log("初始化成功");
    console.log('$', $('#container'));
  }
};
</script>
<style scoped>
#container {
  color: red;
  display: flex;
}
</style>
