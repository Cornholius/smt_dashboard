<script>

export default {
  name: 'Wiki',
  watch: {
    $route: {
      immediate: true,
      handler (to, from) {
        document.title = to.meta.title || 'Вики'
      }
    }
  }
}

</script>
