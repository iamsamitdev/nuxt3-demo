<script lang="ts" setup>

  const route = useRoute()

  console.log(route.params.group)
  console.log(route.params.id)

</script>

<template>
  <div>
    <h1>User Page</h1>
    <h2>Group {{ $route.params.group }}</h2>
    <h2>User {{ $route.params.id }}</h2>
  </div>
</template>

<style scoped></style>
