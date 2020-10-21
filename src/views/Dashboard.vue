<template>
    <div>
      <h3>1234567890</h3>
    </div>
</template>

<script>

export default {
  name: 'Dashboard',
  watch: {
    $route: {
      immediate: true,
      handler (to, from) {
        document.title = to.meta.title || 'Dashboard'
      }
    }
  }
}

</script>
