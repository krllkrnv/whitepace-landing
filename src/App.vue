<template>
  <div class="font-inter overflow-hidden min-h-screen flex flex-col">
    <header-component></header-component>
    <main class="h-full">
      <main-page></main-page>
    </main>
    <footer-component class="w-full h-96"></footer-component>
  </div>
</template>

<script setup>
import FooterComponent from "./components/FooterComponent.vue";
import HeaderComponent from "./components/HeaderComponent.vue";
import MainPage from "./pages/MainPage.vue";
</script>

<style lang="scss" scoped></style>
