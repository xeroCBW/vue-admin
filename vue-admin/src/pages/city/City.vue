<template>
<div>

  <city-header></city-header>
  <city-list></city-list>
  <city-alphabet></city-alphabet>
  <city-search></city-search>
</div>

</template>

<script>

  import CityHeader from './components/Header'
  import CityList from './components/List'
  import CityAlphabet from './components/Alphabet'
  import CitySearch from './components/Search'

  export default {
    name: "City",
    components:{
      CityHeader,
      CityList,
      CityAlphabet,
      CitySearch
    }
  }
</script>

<style lang="stylus" scoped>


</style>
