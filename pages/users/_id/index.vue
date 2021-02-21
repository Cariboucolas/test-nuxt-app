<template>
  <h1>a single user, with ID: {{ $route.params.id }}</h1>
</template>

<script>
export default {
  name: "index",
  validate (data) {
    console.log(data)
    return /^\d+$/.test(data.params.id)
  },
  layout: 'users'
}
</script>

<style scoped>

</style>
