<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <header>
    <nav class="container">
      <div class="branding">
        <img src="../assets/apple.png" alt="apple" />
        <h1>Food Tracker</h1>
      </div>
      <ul class="nav-routes">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </ul>
    </nav>
  </header>
</template>

<style lang="scss" scoped></style>
