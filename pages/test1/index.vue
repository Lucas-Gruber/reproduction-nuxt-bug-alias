<script setup>
const { path } = useRoute()

definePageMeta({
  alias: '/test2',
})
</script>

<template>
  <div>
    <h1>Alias-test-page path: {{ path }}</h1>
    <NuxtLink to="/test1">test1</NuxtLink>
    <br />
    <NuxtLink to="/test2">test2</NuxtLink>
  </div>
</template>
