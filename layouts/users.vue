<template>
  <div>
    <Header />
    <header>
      USERS SECTION
    </header>
    <Nuxt />
  </div>
</template>

<script>
  import Header from "@/components/header";
  export default {
  name: "users",
  component: {
    Header
  }
}
</script>

<style scoped>

</style>
