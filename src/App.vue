<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/login">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/yhch">Yhch</router-link>
    </div> -->
    <router-view />
  </div>
</template>

<style lang="less">
html,body {
  padding: 0;
  margin: 0;
  width: 100%;
  height: 100vh;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  color: #2c3e50;
  width: 100%;
  height: 100%;
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
button {
  cursor: pointer;
}
</style>
