<template>
  <div id="app">
    <img
      class="header-img"
      src="./assets/toben_software_cropped.png"
      alt="toben-software"
    />
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/contact">Contact</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #00b6b9;
  display: flex;
  align-items: center;
  flex-direction: column;
  margin-top: 20px;

  .header-img {
    min-width: 200px;
    max-width: 300px;
    width: 80%;
  }
}

#nav {
  padding: 30px;
  min-width: 220px;
  text-align: center;

  a {
    font-weight: bold;
    color: #00b6b9;

    &.router-link-exact-active {
      color: #0022b5;
    }
  }
}
</style>
