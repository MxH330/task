<template>
  <div id="app">
    <app-header title="白瑞红"></app-header>

    <p>这是A分支的代码</p>
    <p>这是B分支代码</p>
    <router-view></router-view>

  </div>

</template>
<script>
export default {
 
};
</script>


<style lang="scss" scoped>
.tabs {
  width: 100%;
  height: 49px;
  position: absolute;
  left: 0;
  bottom: 0;
  display: flex;
  line-height: 49px;
  text-align: center;
  color: #000;
  flex: 1;
  box-sizing: border-box;
  border-top: 1px solid #ccc;
  #item-a {
    width: 100%;
    height: 100%;
    color: #696969;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    span:first-of-type {
      font-size: 28px;
      line-height: 25px;
    }
    span:last-of-type {
      font-size: 12px;
      line-height: 12px;
    }
  }
}
.router-link-exact-active {
  color: #f03d37 !important;
}
.main-body {
  overflow-y: scroll;
  overflow-x: hidden;
}
.w180 {
  width: 180px;
}
.logo {
  height: 50px;
  padding-top: 5px;
}
.quick-link {
  color: #fff;
  font-size: 24px;
  vertical-align: middle;
  margin-left: 20px;
}
.el-menu-item.is-active {
  color: #00d3c2;
  background: rgba(0, 211, 194, 0.12);
  border-right: 2px solid #00d3c2;
}
</style>
