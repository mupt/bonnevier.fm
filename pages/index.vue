<template>
  <section class="container">
    <name/>
    <links/>
  </section>
</template>

<script>
import name from '~/components/name.vue'
import links from '~/components/links.vue'

export default {
  components: {
    name,
    links
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}


</style>
