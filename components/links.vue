<template>
  <section class="links">
    <ol class="links__group">
      <li class="links__group-item" v-for="link in links">
        <a class="links__group-link" :href="link.href"> {{ link.name }} </a>
      </li>
    </ol>
  </section>
</template>

<script>
export default {
  data () {
    return {
      links: [
        { name: 'LinkedIn', href: 'https://www.linkedin.com/in/f-m-bonnevier-3790b9b1/' },
        { name: 'Github', href: 'https://github.com/mupt' },
        { name: 'Keybase', href: 'https://keybase.io/fbonnevier' }
      ]
    }
  }
}
</script>

<style scoped>
  .links {}

    .links__group {
      display: flex;
    }
      .links__group-item {}

        .links__group-link {
          padding: 16px;
          color: hotpink;
          &:hover {
            color: purple;
          }
        }

</style>
