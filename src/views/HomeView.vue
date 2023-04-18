<script setup lang="ts">
import { ref } from "vue";

const message = ref<string>("Hello")
</script>

<template>
  <main>
    {{message}}
  </main>
</template>
