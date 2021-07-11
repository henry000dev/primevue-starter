<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view/>
</template>

<style lang="scss">
// Uncomment the line below to use a remote font (also update the _theme.scss stylesheet).
// @import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap');
@import "~primevue/resources/primevue.min.css";
@import "./assets/_theme.scss";

#app {
  // Uncomment the line below to use a remote font (also update the _theme.scss stylesheet).
  // font-family: 'Lobster', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
