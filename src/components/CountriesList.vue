
<template lang="html">
  <ul>
    <country-list v-for="(country, index) in countries":country="country" :key="index" >{{country.name}}</country-list>
  </ul>

</template>

<script>
import ListComponent from './ListComponent.vue';
export default {
  name:'countries-list',
  // countries name is need to be same as the :countries
  props: ['countries'],
  components: {
    "country-list": ListComponent
  }
}
</script>

<style lang="css" scoped>
</style>
