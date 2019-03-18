<template>
  <div class="app">
    <div class="nav">
      <router-link to="/">News</router-link> |
      <router-link to="/kalender">Kalender</router-link> |
      <router-link to="/kasse">Kasse</router-link> |
      <router-link to="/team">Team</router-link>
    </div>
    <router-view />
  </div>
</template>

<style>
.app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.nav {
  padding: 30px;
}
</style>
