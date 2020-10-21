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

#main-content {
  text-align: center;
}

</style>
