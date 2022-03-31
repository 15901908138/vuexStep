<template>
  <div class="app">
    <el-card class="login-card">
      <!-- 放置表单容器 -->
      <el-form style="margin-top: 50px;">
        <!-- 表单项 -->
        <el-form-item>
          <!-- 输入框 -->
          <el-input placeholder="请输入用户名"></el-input>
        </el-form-item>
        <el-form-item>
          <!-- 输入框 -->
          <el-input placeholder="请输入密码"></el-input>
        </el-form-item>
        <el-form-item>
          <!-- 按钮 -->
          <el-button style="width: 100%;" type="primary">登录</el-button>
        </el-form-item>
      </el-form>
    </el-card>
  </div>
</template>

<script>
export default {
  name: "App",

  data() {
    return {};
  },

  mounted() {},

  methods: {}
};
</script>

<style scoped>
.app {
  width: 100%;
  height: 100vh;
  background-color: pink;
  display: flex;
  justify-content: center;
  align-items: center;
}
.login-card {
  width: 440px;
  height: 300px;
}

</style>