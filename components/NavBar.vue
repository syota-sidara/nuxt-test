<template>
  <div>
    <nav>
      <nuxt-link to="/">Home</nuxt-link>
      <nuxt-link to="/about" no-prefetch>About</nuxt-link>
      <nuxt-link :to="{name: 'users-list'}">UsersList</nuxt-link>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
