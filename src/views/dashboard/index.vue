<template>
  <div class="dashboard-container" id="#login-img">
    <div class="dashboard-text" style="font-weight: bolder">
      个人博客管理系统
    </div>
    <div>
      基于SpringBoot + MyBatis-Plus + SpringSecurity + Vue的个人博客管理系统。
    </div>
    <div>
      本次项目一共历时9天，后台业务自己独立完成。通过本次项目我学到了很多东西，对规范的项目开发流程有了更加深入的了解，对SpringSecurity安全框架的认证和授权流程有了全新的认识。
    </div>
    <div>
      特别感谢三更老师的辛勤付出和无私奉献。
    </div>
  </div>
</template>

<script>
import { mapGetters } from 'vuex'
export default {
  name: 'Dashboard',
  computed: {
    ...mapGetters([
      'name'
    ])
  }
}
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
