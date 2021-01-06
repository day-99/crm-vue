<template>

  <div class="main-box">
    <el-container >
      <!--      左侧-->
      <el-aside width="200px">
        <div class="title-wrapper">
          <img src="../../assets/suolong.jpg" alt=""/>
          <span>crm后台管理系统</span>
        </div>



        <el-scrollbar class="scrollerbar">
        <el-menu
            default-active="1"
            class="el-menu-vertical-demo">
<!--          不能展开-->
          <el-menu-item index="1">
            <i class="el-icon-menu"></i>
            <span slot="title">系统首页</span>
          </el-menu-item>

<!--         可以展开的导航-->
          <el-submenu index="2">
            <template slot="title">
              <i class="el-icon-location"></i>
              <span>商品相关</span>
            </template>
            <el-menu-item index="2-1">
              <i class="el-icon-menu"></i>
              <span slot="title">品牌管理</span>
            </el-menu-item>

            <el-menu-item index="2-2">
              <i class="el-icon-menu"></i>
              <span slot="title">分类管理</span>
            </el-menu-item>
            <el-menu-item index="2-3">
              <i class="el-icon-menu"></i>
              <span slot="title">商品管理</span>
            </el-menu-item>
          </el-submenu>

          <el-menu-item index="3">
            <i class="el-icon-menu"></i>
            <span slot="title">运营商管理</span>
          </el-menu-item>

          <!--         可以展开的导航-->
          <el-submenu index="2">
            <template slot="title">
              <i class="el-icon-location"></i>
              <span>商品相关</span>
            </template>
            <el-menu-item index="2-1">
              <i class="el-icon-menu"></i>
              <span slot="title">品牌管理</span>
            </el-menu-item>

            <el-menu-item index="2-2">
              <i class="el-icon-menu"></i>
              <span slot="title">分类管理</span>
            </el-menu-item>
            <el-menu-item index="2-3">
              <i class="el-icon-menu"></i>
              <span slot="title">商品管理</span>
            </el-menu-item>
          </el-submenu>
          <!--         可以展开的导航-->
          <el-submenu index="2">
            <template slot="title">
              <i class="el-icon-location"></i>
              <span>商品相关</span>
            </template>
            <el-menu-item index="2-1">
              <i class="el-icon-menu"></i>
              <span slot="title">品牌管理</span>
            </el-menu-item>

            <el-menu-item index="2-2">
              <i class="el-icon-menu"></i>
              <span slot="title">分类管理</span>
            </el-menu-item>
            <el-menu-item index="2-3">
              <i class="el-icon-menu"></i>
              <span slot="title">商品管理</span>
            </el-menu-item>
          </el-submenu>
          <!--         可以展开的导航-->
          <el-submenu index="2">
            <template slot="title">
              <i class="el-icon-location"></i>
              <span>商品相关</span>
            </template>
            <el-menu-item index="2-1">
              <i class="el-icon-menu"></i>
              <span slot="title">品牌管理</span>
            </el-menu-item>

            <el-menu-item index="2-2">
              <i class="el-icon-menu"></i>
              <span slot="title">分类管理</span>
            </el-menu-item>
            <el-menu-item index="2-3">
              <i class="el-icon-menu"></i>
              <span slot="title">商品管理</span>
            </el-menu-item>
          </el-submenu>
          <!--         可以展开的导航-->
          <el-submenu index="2">
            <template slot="title">
              <i class="el-icon-location"></i>
              <span>商品相关</span>
            </template>
            <el-menu-item index="2-1">
              <i class="el-icon-menu"></i>
              <span slot="title">品牌管理</span>
            </el-menu-item>

            <el-menu-item index="2-2">
              <i class="el-icon-menu"></i>
              <span slot="title">分类管理</span>
            </el-menu-item>
            <el-menu-item index="2-3">
              <i class="el-icon-menu"></i>
              <span slot="title">商品管理</span>
            </el-menu-item>
          </el-submenu>
          <!--         可以展开的导航-->
          <el-submenu index="2">
            <template slot="title">
              <i class="el-icon-location"></i>
              <span>商品相关</span>
            </template>
            <el-menu-item index="2-1">
              <i class="el-icon-menu"></i>
              <span slot="title">品牌管理</span>
            </el-menu-item>

            <el-menu-item index="2-2">
              <i class="el-icon-menu"></i>
              <span slot="title">分类管理</span>
            </el-menu-item>
            <el-menu-item index="2-3">
              <i class="el-icon-menu"></i>
              <span slot="title">商品管理</span>
            </el-menu-item>
          </el-submenu>
          <!--         可以展开的导航-->
          <el-submenu index="2">
            <template slot="title">
              <i class="el-icon-location"></i>
              <span>商品相关</span>
            </template>
            <el-menu-item index="2-1">
              <i class="el-icon-menu"></i>
              <span slot="title">品牌管理</span>
            </el-menu-item>

            <el-menu-item index="2-2">
              <i class="el-icon-menu"></i>
              <span slot="title">分类管理</span>
            </el-menu-item>
            <el-menu-item index="2-3">
              <i class="el-icon-menu"></i>
              <span slot="title">商品管理</span>
            </el-menu-item>
          </el-submenu>

        </el-menu>

        </el-scrollbar>
      </el-aside>

      <el-container>
        <el-header>Header</el-header>
        <el-main>Main</el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script>
export default {
  name: "index"

}
</script>

<style scoped lang="less">
//表头
.el-header, .el-footer {
  background-color: #F56C6C;
  color: #fff;
  text-align: center;
  line-height: 60px;
}
//滚动条
.scrollerbar{
  height: calc(100% - 70px);
  width: 110%;
}
//下方滚动条
//.el-aside{
//  overflow:hidden
//}

//左测
.el-aside {
  background-color: #fff;
  color: #444;

  .title-wrapper {
    line-height: 60px;
    background-color: #F56C6C;
    img{
      width: 35px;
      height: 35px;
      border-radius: 50%;
      vertical-align: middle;
      margin: 0 8px 0 10px;
    }
    span{
      font-weight: 700;
      color: white;
      font-size: 16px;
    }
  }
  //导航菜单

}

//表内
.el-main {
  background-color: #E9EEF3;
  color: #333;
  text-align: center;
}

.el-container {
  height: 100%;
}

.main-box {
  height: 100%;
}

</style>