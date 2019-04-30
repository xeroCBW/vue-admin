<template>

  <div>
    <home-header></home-header>
    <home-banner></home-banner>
    <home-icon></home-icon>
    <home-recommend></home-recommend>
    <home-weekend></home-weekend>
  </div>

</template>

<script>

  import HomeHeader from './components/Header'
  import HomeBanner from './components/Banner'
  import HomeIcon from './components/Icon'
  import HomeRecommend from './components/Recommend'
  import HomeWeekend from './components/Weekend'


    export default {
      name: "Home",
      components:{
        HomeHeader,
        HomeBanner,
        HomeIcon,
        HomeRecommend,
        HomeWeekend

      }

    }
</script>

<style lang="stylus" scoped>


</style>
