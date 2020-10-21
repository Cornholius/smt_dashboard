<script>

export default {
  name: 'Mail',
  watch: {
    $route: {
      immediate: true,
      handler (to, from) {
        document.title = to.meta.title || 'Почта'
      }
    }
  }
}

</script>
