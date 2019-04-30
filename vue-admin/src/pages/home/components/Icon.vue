<template>

  <div class="icons">
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <div class="icon-title">景点门票</div>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <div class="icon-title">景点门票</div>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <div class="icon-title">景点门票</div>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <div class="icon-title">景点门票</div>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <div class="icon-title">景点门票</div>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <div class="icon-title">景点门票</div>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <div class="icon-title">景点门票</div>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <div class="icon-title">景点门票</div>
    </div>


  </div>
</template>

<script>
    export default {
        name: "HomeIcon"
    }
</script>

<style lang="stylus" scoped>

  /*.wrapper*/
  .icons
    /*overflow hidden*/
    /*width 100%*/
    height 0
    /*设置顶部距离*/
    padding-top 0.2rem
    padding-bottom 50%
    background-color purple
    .icon
      position relative
      float left
      width 25%
      /*height 50%*/
      height 0
      padding-bottom 25%
      /*background-color orange*/
      overflow hidden
      .icon-img
        position absolute
        left 0
        right 0
        top 0
        bottom 0.4rem
        box-sizing border-box
        padding 0.1rem
        .icon-img-content
          height 100%
          /*设置居中 上下 左右*/
          margin 0 auto
          display block
          /*background-color purple*/
      .icon-title
        position absolute
        margin-top 0.1rem
        left 0
        right 0
        bottom 0.1rem
        text-align center
        /*background-color red*/
        line-height 0.3rem
        font-size 14px
        color #212121



</style>
