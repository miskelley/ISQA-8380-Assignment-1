<template>
  <div class="about">
    <h1>Hello, this is {{their_name}}'s skills list developed in Vue.js to learn Vue.js</h1>
    <p>Vue.js is fun to code in.</p>
  </div>
</template>

<script>
export default {
  name: 'Skills',
data() {
  return {
      their_name: this.$route.params.name
    }
  }
}

</script>

<style>

</style>