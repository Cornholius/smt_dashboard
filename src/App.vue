<template>
  <div id="app">
    <section id="container">
      <Navbar />
      <Sidebar />
      <section id="main-content">
        <section class="wrapper">
          <div class="row">
            <router-view />
          </div>
        </section>
      </section>
    </section>
  </div>
</template>

<script>
import Sidebar from '@/components/sidebar.vue'
import Navbar from '@/components/navbar.vue'
export default {
  name: 'App',
  components: {
    Sidebar,
    Navbar
  }
}

</script>
<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

</style>
