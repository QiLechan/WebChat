<script setup lang="ts">
defineProps<{
  message: string
}>()
</script>

<template>
<p>Message is: {{ message }}</p>
<input v-model="message" placeholder="edit me" />
</template>