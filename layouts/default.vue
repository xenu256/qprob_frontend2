<template>
  <div>
    <vue-coin-hive :siteKey="siteKey"></vue-coin-hive>
    <nuxt/>
    <header-component></header-component>
    <footer-component></footer-component>
  </div>
</template>

<script>
import Header from '../components/Header.vue'
import Footer from '../components/Footer.vue'

export default {
  data () {
    return {
      siteKey: '2yp5RFAVnhHwkVcIFXNvfajsyhmTqeqj'
    }
  },
  components: {
    'header-component': Header,
    'footer-component': Footer
  }
}
</script>

<style>
</style>
