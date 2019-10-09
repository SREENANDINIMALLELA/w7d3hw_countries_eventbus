
<template lang="html">
  <ul>
    <li v-for="(country, index) in countries" >{{country.name}}</li>

    <!-- <li v-for="(country, index) in countries"  :country="country" :key="index">nnn</li> -->
  </ul>

</template>

<script>
// import CountryList from './countryListOption.vue';
export default {
  name:'countries-list',
  props: ['countries'],
  // components: {
  //   "country-list": CountryList
  // }
}
</script>

<style lang="css" scoped>
</style>
