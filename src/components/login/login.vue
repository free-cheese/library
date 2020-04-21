<template>
    <div class="login" name="login">
      <el-form :label-position="labelPosition" label-width="80px" :model="login">
        <el-form-item label="用户名">
          <el-input v-model="login.name"></el-input>
        </el-form-item>
        <el-form-item label="密码">
          <el-input v-model="login.password"></el-input>
        </el-form-item>
      </el-form>
    </div>
</template>

<script>
    export default {
      name: "login",
      data() {
        return {
          labelPosition: 'right',
          formLabelAlign: {
            name: '',
            password: '',
            type: ''
          }
        };
      }
    }
</script>

<style scoped>

</style>
