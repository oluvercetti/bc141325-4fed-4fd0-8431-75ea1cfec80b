<script setup lang="ts">
import CreateTask from '@/components/CreateTask.vue'
</script>
<template>
  <main class="create__task--container">
    <h1 class="create__task--header">Create Task</h1>
    <CreateTask />
  </main>
</template>
<style scoped>
.create__task--container {
  @apply bg-white px-[5%] py-[2%] flex flex-col gap-4;
}

.create__task--header {
  @apply text-black font-[700] text-[24px];
}
</style>
