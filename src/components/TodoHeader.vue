<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
  <header>
    <nav class="container">
      <div class="branding">
        <img src="@/assets/Todo_Logo.png" alt="" />
        <h1>M's Todos</h1>
      </div>
      <ul class="nav-routes">
        <RouterLink :to="{ name: 'todos' }">Todos</RouterLink>
        <RouterLink :to="{ name: 'about' }">About</RouterLink>
      </ul>
    </nav>
  </header>
</template>

<style lang="scss" scoped>
header {
  background-color: #fff;
  nav {
    display: flex;
    align-items: center;
    padding: 25px 16px;

    .branding {
      display: flex;
      align-items: center;
      gap: 2px;
      img {
        max-width: 70px;
      }

      h1 {
        font-size: 24px;
      }
    }

    .nav-routes {
      display: flex;
      flex: 1;
      justify-content: flex-end;
      gap: 12px;
      list-style: none;

      a {
        text-decoration: none;
        color: inherit;
      }
    }
  }
}
</style>
