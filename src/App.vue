<template>
  <!--应用只有一个页面 index.html App.vue 这里面的内容 就是显示在index。html当中的这里面写啥 index里面就展示啥
  表示不确定显示的内容

  -->
  <div class="app-box">
    <router-view/>
  </div>
</template>

<style lang="less">
//清楚所有的内外边距
* {
  margin: 0;
  padding: 0;
}
html,body,.app-box{
  width: 100%;
  height: 100%;
}

</style>
