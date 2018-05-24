<template lang="pug">
  div
    nuxt
</template>

<style lang="sass">
@import '@/assets/css/bulma-init.scss'
@import url('https://fonts.googleapis.com/earlyaccess/notosansjapanese.css')
@import url('https://fonts.googleapis.com/css?family=Raleway:400,500,600,700,800,900')

body
  font-family: "Noto Sans Japanese", -apple-system, BlinkMacSystemFont, "Helvetica Neue", "Yu Gothic", YuGothic, "ヒラギノ角ゴ ProN W3", Hiragino Kaku Gothic ProN, Arial, "メイリオ", Meiryo, sans-serif;
  color: black
  max-width: 768px
  margin: 0 auto

.container
  max-width: 768px

*, *::after, *::before
  box-sizing: border-box

a
  color: inherit

.raleway
  font-family: 'Raleway', 'sans-serif'
  letter-spacing: 0.03em
</style>