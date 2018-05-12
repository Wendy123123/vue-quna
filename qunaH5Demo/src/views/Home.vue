<template>
  <div class="home">
      <home-header></home-header>
  </div>
</template>

<script>
import HomeHeader from '@/components/HomeHeader'
export default {
  name: 'Home',
  components: { HomeHeader },
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" scoped>

</style>
