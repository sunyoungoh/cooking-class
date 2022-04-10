<template>
  <v-app class="app">
    <AppHeader />
    <v-main class="app-contents">
      <router-view />
    </v-main>
    <AppFooter />
  </v-app>
</template>

<script>
import AppHeader from '@/components/common/AppHeader.vue';
import AppFooter from '@/components/common/AppFooter.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppFooter,
  },
};
</script>

<style>
@import './styles/reset.css';
@import './styles/common.css';
</style>
