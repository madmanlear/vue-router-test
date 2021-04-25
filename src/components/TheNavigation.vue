<template>
  <nav id="nav">
    <router-link to="/">Home</router-link>
    <router-link to="/brazil">Brazil</router-link>
    <router-link to="/hawaii">Hawaii</router-link>
    <router-link to="/jamaica">Jamaica</router-link>
    <router-link to="/panama">Panama</router-link>
  </nav>
</template>

<style scoped>
#nav {
  display: flex;
  justify-content: center;
}

#nav a {
  color: #2c3e50;
  font-weight: bold;
  padding: 0 10px;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
