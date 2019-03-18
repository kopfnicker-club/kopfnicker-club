<template>
  <section class="section">
    <div class="container">
      <nav class="level">
        <p class="level-item has-text-centered">
          <router-link class="link is-info" to="/">News</router-link>
        </p>
        <p class="level-item has-text-centered">
          <router-link class="link is-info" to="/kalender">Kalender</router-link>
        </p>
        <p class="level-item has-text-centered">
          <router-link class="link is-info" to="/kasse">Kasse</router-link>
        </p>
        <p class="level-item has-text-centered">
          <router-link class="link is-info" to="/team">Team</router-link>
        </p>
      </nav>
    </div>
    <router-view />
  </section>
</template>

<style>
.app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
