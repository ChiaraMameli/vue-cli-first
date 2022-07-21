<template>
  <div class="container">
    <MyTitle />
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue'
export default {
  name: 'App',
  components: {
    MyTitle: MyTitle ,
}
}
</script>

<style lang="scss">
.container{
  width: 80%;
  margin: 0 auto;
}
</style>
