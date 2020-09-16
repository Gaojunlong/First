<template>
  <div>
    <div>
      <el-row :gutter="5">
        <el-col :span="2"><div class="grid-content bg-purple">发布单位：</div></el-col>
        <el-col :span="2"><div class="grid-content bg-purple">全部</div></el-col>
        <el-col :span="3"><div class="grid-content bg-purple">国家卫生健康委</div></el-col>
        <el-col :span="3"><div class="grid-content bg-purple">湖北政府办公厅</div></el-col>
        <el-col :span="3"><div class="grid-content bg-purple">北京市政府办公厅</div></el-col>
        <el-col :span="3"><div class="grid-content bg-purple">江苏省政府办公厅</div></el-col>
        <el-col :span="5"><div class="grid-content bg-purple">新疆生产建设兵团政府办公厅</div></el-col>
        <el-col :span="2"><div class="grid-content bg-purple">收起</div></el-col>
      </el-row>
    </div>
    <div>
      <el-row :gutter="5">
        <el-col :span="2"><div class="grid-content bg-purple">其他选项</div></el-col>
        <div>
          <el-col :span="2"><div class="grid-content bg-purple">发布单位：</div></el-col>
        </div>
      </el-row>
    </div>
  </div>
</template>
<style>
  .el-row {
    margin-bottom: 20px;
    
  }
  .el-col {
    border-radius: 4px;
    
  }
  .bg-purple-dark {
    background: #ffffff;
  }
  .bg-purple {
    background: #ffffff;
  }
  .bg-purple-light {
    background: #ffffff;
  }
  .grid-content {
    border-radius: 4px;
    min-height: 36px;
  }
  .row-bg {
    padding: 10px 0;
    background-color: #f9fafc;
  }
</style>