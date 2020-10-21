<template>
    <Table />
</template>

<script>
// @ is an alias to /src
import Table from '@/components/request_table.vue'

export default {
  name: 'requests',
  components: {
    Table
  },
  watch: {
    $route: {
      immediate: true,
      handler (to, from) {
        document.title = to.meta.title || 'Заявки'
      }
    }
  }
}

</script>
