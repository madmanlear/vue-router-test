<template>
  <nav id="nav">
    <router-link to="/">Home</router-link>
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
