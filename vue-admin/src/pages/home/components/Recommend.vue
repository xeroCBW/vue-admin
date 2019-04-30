<template>

  <div>

    <div class="title border-bottom">
      <img class="title-img" src="http://img1.qunarzz.com/piao/fusion/1711/89/ebc329f16c55bb02.png" alt="">
      <span class="title-desc">去哪儿推荐</span>
    </div>
    <div class="list">
      <div class="item border-bottom">
        <img class="item-img" src="http://img1.qunarzz.com/sight/p0/1904/1e/1e51b5ea32ee8033a3.water.jpg_200x200_7750aa0b.jpg" alt="">
        <div class="item-info">
          <p class="item-info-title">深圳欢乐谷深圳欢乐谷深圳欢乐谷深圳欢乐谷深圳欢乐谷深圳欢乐谷</p>
          <p class="item-info-desc">6830条评论</p>
          <input type="button" class="item-info-button" value="获取详情">
        </div>
      </div>
    </div>
  </div>

</template>

<script>
    export default {
        name: "HomeRecommend"
    }
</script>

<style lang="stylus" scoped>
  @import "../../../assets/style/mixins.styl"

  .border-topbottom
    &:before
      border-color #ccc
    &:before
      border-color #ccc
  .border-bottom
    &:before
      border-color #ccc
  .title
    /*background-color red*/
    height 0.8rem
    .title-img
      /*background-color #25a4bb*/
      display inline-block
      width 0.4rem
      height 0.4rem
      margin-left 0.2rem
      margin-bottom  0.1rem
    .title-desc
      display inline-block
      margin-top 0.1rem
      /*margin-left 0.8rem*/
      height 0.6rem
      line-height 0.6rem
      font-size 16px
      /*background-color green*/
  .list
    /*background-color green*/
    .item
      padding-left 0.2rem
      display flex
      /*background-color red*/
      height 2.0rem
      overflow hidden
      .item-img
        height 1.8rem
        width 1.8rem
        margin-top 0.1rem
      .item-info
        flex 1
        padding 0.1rem 0.2rem
        /*设置了宽度才会显示...*/
        min-width 0
        /*background-color #25a4bb*/
        .item-info-title
          ellipsis()
          font-size 14px
          line-height 0.6rem
          height 30px
        .item-info-desc
          ellipsis()
          line-height 0.4rem
          font-size 12px
          color lightgrey
        .item-info-button
          margin-top 0.1rem
          background-color orange
          border-radius 0.1rem
          padding 0.1rem 0.5rem








</style>
