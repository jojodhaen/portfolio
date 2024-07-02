<script lang="ts" setup></script>

<template>
  <header>
    <div class="nav-container">
      <router-link class="name" to="/">JOREN</router-link>
      <nav>
        <router-link class="nav-link" to="/">Projecten</router-link>
        <router-link class="nav-link" to="/">Over Mij</router-link>
        <router-link class="nav-link" to="/">Contact</router-link>
      </nav>
    </div>
  </header>
</template>

<style scoped>
header {
  background-color: #333;
  padding: 1rem;
  text-align: center;
}

.nav-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 1rem;
}

.name {
  font-size: 2.5rem;
  font-family: 'Space Mono', monospace;
  font-weight: bold;
  color: white;
  text-decoration: none;
}

nav {
  display: flex;
  gap: 1.5rem;
}

.nav-link {
  text-decoration: none;
  color: white;
  font-size: 1.25rem;
  font-family: 'Space Mono', monospace;
}
</style>
