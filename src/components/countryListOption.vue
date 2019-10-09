<template lang="html">
<li>{{country.name}}</li>
</template>

<script>
export default {
  name: 'country-list',
  props: ['country']
}
</script>

<style lang="css" scoped>
</style>
