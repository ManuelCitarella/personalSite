<script setup lang="ts">

</script>

<template>
    <div class="menu">  
      <div class="links">
          <a class="link" target="_blank" rel="noopener">Vite</a> 
          <a  class="link" target="_blank" rel="noopener">Vue 3</a>
          <a  class="link" target="_blank" rel="noopener">Vue 3</a>
          <a  class="link" target="_blank" rel="noopener">Vue 3</a>
      </div>
    </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.menu {
display: flex;
justify-content: space-between;
}

.links{
  display: flex;
  justify-content: space-between;
  justify-items: center;
  .link{
    padding: 0.5rem;
    text-align: center;
  }
}


@media (min-width: 1024px) {
  .menu{
    display: flex;
    justify-content: space-between;
  }
}
</style>
