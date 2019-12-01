<template>
  <div class="home">
    <el-table :data="tableData" style="width: 100%">
      <el-table-column prop="a" label="测试数据"> </el-table-column>
      <el-table-column prop="b" label="测试数据2"> </el-table-column>
    </el-table>
  </div>
</template>

<script>
export default {
  name: 'home',
  data() {
    return {
      tableData: [
        {
          a: '1',
          b: '2'
        }
      ]
    }
  }
}
</script>
