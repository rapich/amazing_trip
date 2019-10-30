<template lang="pug">
  div
    v-app
      NavBar
      v-container
        nuxt
</template>

<script>
import NavBar from '@/components/NavBar.vue'

export default {
  components: {
    NavBar
  }
}
</script>
