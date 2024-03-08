<script lang="ts">
import {defineComponent} from 'vue'

export default defineComponent({
  name: "index",
  setup() {
    definePageMeta({
      layout: 'admin'
    })

    return {}
  }
})
</script>

<template>
  <div>
    admin index page
    <nuxt-link to="/admin/users">Admin Users</nuxt-link>
    <nuxt-page />
  </div>
</template>

<style scoped>

</style>
