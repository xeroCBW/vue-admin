<template>
  <div>
    <div class="header">
      <div class="header-left">返回</div>
      <div class="header-input">
         输入城市/经典/游玩主题
      </div>
      <router-link to="/city">
        <div class="header-right">城市</div>
      </router-link>
    </div>
  </div>
</template>

<script>
    export default {
        name: "HomeHeader"
    }
</script>

<style lang="stylus" scoped>

  1 rem = 50px

  .header
    display flex
    background-color #00bcd4
    height 0.88rem
    .header-left
      float left
      /*background-color red*/
      line-height 0.88rem
      width 1rem
      text-align center
      color white
    .header-input
      /*这里设置成flex 1*/
      flex 1
      background-color white
      border-radius 0.1rem
      margin 0.1rem 0.2rem
      line-height 0.68rem
      color lightgrey
      text-align center
    .header-right
      float right
      /*background-color yellow*/
      min-width 1rem
      line-height 0.88rem
      text-align center
      color white






</style>
