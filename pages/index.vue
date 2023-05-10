<template>
  <main>
      <h1>Homepage</h1>
      <ul>
          <li>
              <nuxt-link to="/about">About</nuxt-link>
          </li>
          <li> <nuxt-link to="/contact">Contact</nuxt-link> </li>

      </ul>
      <h2>
          Produits
      </h2>
      <ul>
          <li>
              <nuxt-link to="/product/1">Produit 1</nuxt-link>
          </li>
          <li> <nuxt-link to="/product/2">Produit 2</nuxt-link> </li>
          <li> <nuxt-link to="/product/3">Produit 3</nuxt-link> </li>

      </ul>
      <h2></h2>
  </main>
</template>

<script>
export default {
    name: "index.vue"
}
</script>

<style scoped>

</style>