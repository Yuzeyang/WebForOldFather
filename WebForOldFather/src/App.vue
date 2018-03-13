<template>
  <div>
    <div id="banner">
      <div>
        <img src="" alt="">
        <label for="">绍兴圣御山酒业</label>
      </div>
      <div id="tab">
        <button id="tab-button">首页</button>
        <button id="tab-button">走进企业</button>
        <button id="tab-button">品牌文化</button>
        <button id="tab-button">产品展示</button>
        <button id="tab-button">黄酒文化</button>
        <button id="tab-button">联系我们</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#banner {
  height: 50px;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

#tab {
  width: 500px;
  display: flex;
  justify-content: space-around;
}

#tab-button {
  border-style: none;
}
</style>
