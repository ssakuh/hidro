<template>
  <div class="content has-text-centered">
    <h1 class="is-title is-bold">HidroAdmin</h1>

    <p>
      <strong>Trofeul Hidrotehnicii 2019</strong>,
      <a :href="homepage">Demo Live</a>
    </p>


  </div>
</template>

<script>
export default {

  data () {
    return this.$store.state.pkg
  }

}
</script>

<style lang="scss" scoped>
.is-title {
  text-transform: capitalize;
}
</style>
