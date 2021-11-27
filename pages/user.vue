<template>
  <div>
    <h1>User page</h1>
    <nuxt-link to="/"><button>Home</button></nuxt-link>
  </div>
</template>

<script>
export default {
  middleware: 'user'
}
</script>
