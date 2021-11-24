<template>
  <div class="dashboard-container" style="display: flex">
    <el-card class="box-card" style="flex: 1">
      <div slot="header" class="clearfix">
        <span style="color: #000000; font-weight: 600"
          >Vue、Spring Boot物业管理项目实战视频教程</span
        >
      </div>
      <div class="text item">
        <div style="color: #000000; font-weight: 600">学前要求</div>
        <div style="padding: 10px 30px">有Html、CSS、Js、Vue、Spring Boot的基础</div>
        <div style="color: #000000; font-weight: 600">使用技术</div>
        <div style="padding: 10px 30px">Vue、Element、vue-admin-template</div>
        <div style="padding: 10px 30px">Java、Spring Boot2.4、Jwt、token</div>
        <div style="padding: 10px 30px">Spring Security安全框架</div>
        <div style="padding: 10px 30px">MySql5.7及以上</div>
         <div style="padding: 10px 30px">PowerDesigner</div>
        <div style="color: #000000; font-weight: 600">教学方式</div>
        <div style="padding: 10px 30px">全程手把手带领敲代码，从0开始搭建项目;</div>
        <div style="color: #000000; font-weight: 600">学习收获</div>
        <div style="padding: 10px 30px">学会使用vue-admin-template开发后台系统;</div>
        <div style="padding: 10px 30px">vue后台系统中登录、权限权限验证流程;</div>
        <div style="padding: 10px 30px">
          vue动态菜单、动态路由、按钮权限实现原理，代码实现;
        </div>
        <div style="padding: 10px 30px">
          通用弹框、tree组件优化、页面优化、通用axios封装、restful api支持封装;
        </div>
        <div style="padding: 10px 30px">前后端分离中的token(JWT)验证;</div>
        <div style="padding: 10px 30px">学会使用Spring Boot开发前端后端分离项目;</div>
        <div style="padding: 10px 30px">学会Spring Security在前后端分离项目中的使用;</div>
        <div style="padding: 10px 30px">
          从0到1完成一个基于Vue、Spring Boot的前后端分离项目;
        </div>
      </div>
    </el-card>
    <el-card class="box-card" style="flex: 1">
      <div slot="header" class="clearfix">
        <span style="color: #000000; font-weight: 600">我们的服务</span>
      </div>
      <div class="text item">
        <div style="color: #000000; font-weight: 600">服务项目</div>
        <div style="padding: 10px 30px">提供课程的视频、源码、课程笔记；</div>
        <div style="padding: 10px 30px">一对一答疑，不限次数；</div>
        <div style="padding: 10px 30px">
          售后答疑，包括课程中遇到的问题、工作中的问题也可以；
        </div>
        <div style="color: #000000; font-weight: 600;margin-top:20px;color: #FF7670;">服务须知</div>
        <div style="padding: 10px 30px"><span>购买课程的小伙伴，加</span><span style="color:blue;font-weight: 600;">QQ：3501754007</span><span>解决课程中的问题；</span></div>
      </div>
    </el-card>
  </div>
</template>

<script>
import { mapGetters } from "vuex";

export default {
  name: "Dashboard",
  computed: {
    ...mapGetters(["name"]),
  },
};
</script>

<style lang="scss" scoped>
.dashboard {
  &-container {
    margin: 30px;
  }
  &-text {
    font-size: 30px;
    line-height: 46px;
  }
}
</style>
