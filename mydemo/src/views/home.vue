<template>
  <div>
    <h1>欢迎光临</h1>
    <div id="con"></div>
  </div>
</template>

<script>

export default {
  data() {
    return {};
  },
  mounted() {
    let myChart = this.$eh.init(document.getElementById("con"));
    //创建配置项
    let option = {
      xAxis:{
        type:"category",
        data:[]
      }
    }
  },
};
</script>

<style  lang="" scoped>
</style>
