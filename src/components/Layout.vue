<template>
  <Header />
  <main>
    <router-view></router-view>
  </main>
</template>

<script setup>
import Header from './Header.vue';
import { RouterView } from 'vue-router';
</script>


