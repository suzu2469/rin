<template lang="pug">
  nav.menu.is-size-4
    p.menu-content: a(href="#top", v-smooth-scroll="{ duration: 1000 }") TOP
    p.menu-content: a(href="#profile", v-smooth-scroll="{ duration: 1000 }") PROFILE
    p.menu-content: a(href="#works", v-smooth-scroll="{ duration: 1000 }") WORKS
    p.menu-content: a(href="#skills", v-smooth-scroll="{ duration: 1000 }") SKILLS
    p.menu-content: a(href="#links", v-smooth-scroll="{ duration: 1000 }") LINKS
</template>

<script>
import vueSmoothScroll from 'vue-smooth-scroll'
import Vue from 'vue'

Vue.use(vueSmoothScroll)
</script>

<style lang="sass" scoped>
.menu
  position: fixed
  right: 0
  top: 0
  z-index: 9
  text-align: right
  color: white;
  .menu-content
    &::after
      content: '\A'
    a
      background-color: black
      &:hover
        color: inherit
</style>