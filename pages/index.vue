<script lang="ts">
import {defineComponent} from 'vue'

export default defineComponent({
  name: "index"
})
</script>

<template>
  <div>
    index page
    <nuxt-link to="/admin">
      Admin index
    </nuxt-link>
  </div>
</template>

<style scoped>

</style>
