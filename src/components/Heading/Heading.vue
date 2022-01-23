<script setup lang="ts">
import {defineProps} from 'vue'

defineProps<{ name: string, logo: string }>()

</script>

<template>
  <h1>{{ name }}</h1>
  <img :src="logo" alt="logo">
</template>
