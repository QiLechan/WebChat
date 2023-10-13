<script setup lang="ts">
defineProps({
  message: String
})
</script>

<template>
<p>Message is: {{ message }}</p>
<input v-model="message" placeholder="edit me" />
</template>