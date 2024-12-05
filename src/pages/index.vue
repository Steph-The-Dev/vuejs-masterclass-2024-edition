<template>
  <div>
    <h1>Projects</h1>
    <RouterLink :to="{ name: '/projects/[id]', params: { id: 1 } }">Go to project 1</RouterLink>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>
