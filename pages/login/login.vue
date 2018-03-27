<template>
    <div class="login-con">
        {{name}}
    </div>
</template>

<script type="text/ecmascript-6">
    export default {
      data(){
        return{
          name:'这是登录页'
        }
      }
    }
</script>

<style>
.login-con {
  width: 200px;
  height: 100px;
  line-height: 100px;
  text-align: center;
  margin: auto;
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
}
</style>
