<template>
  <div id="app-container">
    <AppHeader />
    <div class="container mt-3">
      <router-view />
    </div>
  </div>
</template>

<script>
  import AppHeader from "./components/AppHeader.vue";
  export default {
    components: {
      AppHeader,
    },
  };
</script>

<style>
  .page {
    max-width: 600px;
    margin: auto;
  }
</style>
