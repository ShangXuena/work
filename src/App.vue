<template>
  <div id="app">
    <home-header></home-header>


    <home-footer></home-footer>
  </div>
</template>

<script>

import homeFooter from './components/homeFooter'
import homeHeader from './components/homeHeader'

export default {
  name: 'app',
  components: {
    homeHeader,
    homeFooter
  }
}
</script>

<style>

</style>
