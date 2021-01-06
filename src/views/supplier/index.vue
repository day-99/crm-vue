<template>
<div class="entity-box">
<!--  操作的部分-->
  <div class="execute-box">
    <el-button-group>
    <el-button type="primary" plain>新建</el-button>
    <el-button type="primary" plain>批量删除</el-button>
    </el-button-group>
  </div>
<!--  查询-->
  <div class="search-box"></div>

<!--  表单数据
border 带边框
stripe 斑马状
tooltip-effect="dark" //表格内信息过长的话显示省略号/不换行

-->
  <div class="table-box">
    <el-table
        stripe
        border
        tooltip-effect="dark"
        :data="tableData"
        style="width: 100%">
<!--      选择框-->
      <el-table-column
          align="center"
      type="selection"
      width="55"
      ></el-table-column>
      <el-table-column
          align="center"
          prop="date"
          label="日期"
          width="180">
      </el-table-column>
      <el-table-column
          align="center"
          prop="name"
          label="姓名"
          width="180">
      </el-table-column>
      <el-table-column
          align="center"
          prop="address"
          label="地址">
      </el-table-column>

      <el-table-column
          align="center"
          label="操作">
<!--        要取值得话需要加上 template-->
        <template>
          <el-button size="mini" type="primary">编辑</el-button>
          <el-button size="mini" type="danger">删除</el-button>
        </template>

      </el-table-column>
    </el-table>
  </div>

<!--  分页-->
<div class="page-box">
  <el-pagination
      background
      layout="prev, pager, next"
      :total="1000">
  </el-pagination>
</div>

</div>




</template>

<script src="./index.js">
</script>

<style scoped src="./index.less" lang="less">

</style>