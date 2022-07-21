<template>
  <div class="container">
    <MyTitle />
    <MyHero />
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue'
import MyHero from './components/MyHero.vue'

export default {
  name: 'App',
  components: {
    MyTitle,
    MyHero,
}
}
</script>

<style lang="scss">
.container{
  width: 80%;
  margin: 0 auto;
  text-align: center;
}
</style>
