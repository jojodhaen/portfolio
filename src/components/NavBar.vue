<script lang="ts" setup></script>

<template>
  <header>
    <div class="nav-container">
      <span class="name">JOREN</span>
      <nav>
        <router-link class="nav-link" to="/">PROJECTEN</router-link>
        <router-link class="nav-link" to="/">OVER MIJ</router-link>
        <router-link class="nav-link" to="/">CONTACT</router-link>
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
}

nav {
  display: flex;
  gap: 1rem;
}

.nav-link {
  display: flex;
  gap: 1rem;
  text-decoration: none;
  color: white;
  font-size: 1.25rem;
}
</style>
