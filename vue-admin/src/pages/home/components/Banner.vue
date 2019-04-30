<template>
<div>
  <div class="banner">
    <swiper :options="swiperOption" ref="mySwiper">
      <!-- slides -->
      <swiper-slide>
        <img class="swiper-img" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20194/e9f92741ef8b1cb0472ced96150d0d1c.jpg_750x200_1f0a2392.jpg" alt="">
      </swiper-slide>
      <swiper-slide>
        <img class="swiper-img" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20194/e0c5d91cb9b435518bb223b81b70874e.jpg_750x200_f2d5c66a.jpg" alt="">
      </swiper-slide>

      <!-- Optional controls -->
      <div class="swiper-pagination"  slot="pagination"></div>
      <!--<div class="swiper-button-prev" slot="button-prev"></div>-->
      <!--<div class="swiper-button-next" slot="button-next"></div>-->
      <div class="swiper-scrollbar"   slot="scrollbar"></div>
    </swiper>
  </div>
</div>
</template>

<script>
    export default {
      name: "HomeBanner",
      data() {
        return {
          swiperOption: {
            loop:true,
            autoplay:true
            // some swiper options/callbacks
            // 所有的参数同 swiper 官方 api 参数
            // ...
          }
        }
      },
      computed: {
        swiper() {
          return this.$refs.mySwiper.swiper
        }
      },
      mounted() {
        // current swiper instance
        // 然后你就可以使用当前上下文内的swiper对象去做你想做的事了
        console.log('this is current swiper instance object', this.swiper)
        this.swiper.slideTo(3, 1000, false)
      }
    }
</script>

<style lang="stylus" scoped>

  .banner
    overflow hidden
    width  100%
    height 0
    padding-bottom 27%
    .swiper-img
      width 100%



</style>
