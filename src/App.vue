<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<style lang="scss">
  #app {
    .layout {
      background: #00CE00;
      position: relative;
      overflow: hidden;
    }
    .layout-logo {
      float: left;
      position: relative;
      top: 5px;
      margin-bottom: 10px
    }
    .layout-nav {
      width: 800px;
      margin: 0 auto;
      margin-right: 20px;
    }
    .layout-footer{
      position: relative;
      text-align: right;
      bottom: 0;
      width: 100%;
    }

  }
</style>