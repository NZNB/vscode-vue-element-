  <el-menu
    default-active="1"
    background-color="#fff"
    text-color="#fff"
    active-text-color="#ffd04b"
    router
    @close="handleClose"
    @open="handleOpen">
    <el-menu-item index="">
      <span slot="title">导航一</span>
    </el-menu-item>
    <el-menu-item index="">
      <span slot="title">导航二</span>
    </el-menu-item>
    <el-menu-item index="" disabled>
      <span slot="title">导航三</span>
    </el-menu-item>
    <el-menu-item index="">
      <span slot="title">导航四</span>
    </el-menu-item>
  </el-menu>
