<template lang="pug">
  div
    v-toolbar
      v-toolbar-title Amazing Trip
      v-spacer
      v-toolbar-items
        v-btn(text)
          nuxt-link(to='/') Home
        v-btn(text)
          nuxt-link(to='/about') About
</template>

<style scoped lang="sass">
a
  text-decoration: none
  color: black
</style>
