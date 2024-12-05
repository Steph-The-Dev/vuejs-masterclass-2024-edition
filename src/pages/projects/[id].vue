<template>
  <div>Single Project View on {{ route.params?.id }}</div>
</template>

<script setup lang="ts">
import { useRoute } from 'vue-router'

const route = useRoute()
</script>

<style scoped></style>
