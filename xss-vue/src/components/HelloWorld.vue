<template>
  <div class="hello">
    <h1>Hello {{ $route.params.name }}</h1>
    <span v-html="$route.params.name"></span>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'test'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
