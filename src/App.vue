<script setup lang="ts">
import HelloWorld from "./components/HelloWorld.vue";
import TheWelcome from "./components/TheWelcome.vue";
</script>

<template>
  <header class="header-menu">
    <img
      alt="Vue logo"
      class="logo"
      src="./assets/logo.svg"
      width="50"
      height="50"
    />

    <div class="wrapper">
      <HelloWorld />
    </div>

  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
    place-items: center;
}

.header-menu{
  display: flex;
  justify-content: space-between;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
