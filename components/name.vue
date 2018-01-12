<template>
  <p>
    {{ name.first }}
    {{ name.last }}
  </p>
</template>

<script>
export default {
  data () {
    return {
      name: {
        first: 'f.m.',
        last: 'bonnevier'
      }
    }
  }
}
</script>

<style scoped>
  .links {}
    .links__link {
      color: #b4da55;
    }
</style>
