<script setup lang="ts">
import SiteHeader from "@/layouts/SiteHeader.vue";
import SiteFooter from "@/layouts/SiteFooter.vue";
</script>

<template>
  <div id="app">
    <SiteHeader />
    <RouterView />
    <SiteFooter />
  </div>
</template>
