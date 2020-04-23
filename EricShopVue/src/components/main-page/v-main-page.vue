<template>
  <div class='v-main-page'>
    <h1>ShopEric</h1>
    <p>
      <router-link :to="{name: 'catalog'}">
        <h1>Каталог</h1>
      </router-link>
    </p>
  </div>
</template>

<script>
  export default {
    name: "v-main-page",
    props: {},
    data() {
      return {}
    },
    computed: {}
  }
</script>

<style scoped>

</style>
