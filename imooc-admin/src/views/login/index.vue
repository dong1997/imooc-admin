<template>
  <div class="login-container">
    <el-form class="login-form">
      <div class="title-container">
        <h3 class="title">用户登录</h3>
      </div>

      <el-form-item prop="username">
        <span class="svg-container">
          <el-icon>
            <Avatar/>
          </el-icon>
        </span>
        <el-input placeholder="username" name="username" type="text"> 
        </el-input>
      </el-form-item>

      <el-form-item prop="password">
        <span class="svg-container">
          <el-icon>
            <Avatar/>
          </el-icon>
        </span>
        <el-input placeholder="username" name="username" > 
        </el-input>
        <span class="show-pwd">
          <el-icon>
            <Avatar/>
          </el-icon>
        </span> 
      </el-form-item>
    </el-form>

    <el-button type="primary" style="width: 100%; margin-bottom: 30px;">
      登录
    </el-button>
  </div>
</template>

<script setup>
import {} from 'vue'
import { Avatar } from '@element-plus/icons'
</script>

<style lang="scss" scoped>
</style>
