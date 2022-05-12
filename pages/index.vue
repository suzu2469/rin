<template lang="pug">
  div#top
    Menu
    main
      section.hero.is-fullheight#tom
        .hero-body
          .container
            .title
              img(src="@/assets/img/common/rin-logo.svg").title-logo
      section.section#profile
        .container
          h1.title.raleway Profile
          h2.subtitle 自己紹介
          section.profile-head
            .profile-me
              img(src="@/assets/img/top/profile-me.png")
            p.body.has-text-centered ❛❛ 毎食ロイホのパフェだけで生きたい❜❜
            h3.namefolio.has-text-centered.is-size-2 Souma Suzuki
          section.detail.is-size-5
            h1.raleway.title.is-size-6 Detail
            .columns.is-mobile
              .column.is-5 Age
              .column.is-7 22
            .columns.is-mobile
              .column.is-5 Residence
              .column.is-7 東京都
          section.career.is-size-5
            h1.raleway.title.is-size-6 Career
            .columns.is-mobile
              .column.is-5 2015 / 04
              .column.is-7 株式会社リコー<br>
                p.is-size-7 プラント機械保全エンジニア
            .columns.is-mobile
              .column.is-5 2016 / 07
              .column.is-7 株式会社10バトン<br>
                p.is-size-7 ExcelVBAエンジニア
            .columns.is-mobile
              .column.is-5 2017 / 08
              .column.is-7 株式会社ENO
                p.is-size-7 WEBフルスタックエンジニア
            .columns.is-mobile
              .column.is-5 2018 / 03
              .column.is-7 フリーランス
                p.is-size-7 エンジニア & デザイナー
            .columns.is-mobile
              .column.is-5 2018 / 06
              .column.is-7 都内某所
                p.is-size-7 フロントエンドエンジニア
      section.section#works
        .container
          h1.title.raleway WORKS
          h2.subtitle ポートフォリオ
          p.is-size-3.has-text-centered(style="font-weight: 600; letter-spacing: 0.5em; margin: 3.0rem") 準備中<br>(すまん)
      section.section#skills
        .container
          h1.title.raleway SKILLS
          h2.subtitle できること
          .columns.is-mobile.skill-icons
            .column.is-4.align-center
              img(src="@/assets/img/common/vue.svg")
            .column.is-4.align-center
              img(src="@/assets/img/common/react.svg")
            .column.is-4.align-center
              img(src="@/assets/img/common/typescript.svg")
          .columns.is-mobile
            .column.is-3.align-center
              img(src="@/assets/img/common/go.svg")
            .column.is-3.align-center
              img(src="@/assets/img/common/nuxt.svg")
            .column.is-3.align-center
              img(src="@/assets/img/common/HTML5_Badge.svg")
            .column.is-3.align-center
              img(src="@/assets/img/common/sass.svg")
          .columns.is-mobile
            .column.is-3.align-center
              img(src="@/assets/img/common/django-logo-positive.svg")
            .column.is-3.align-center
              img(src="@/assets/img/common/docker.png")
            .column.is-3.align-center
              img(src="@/assets/img/common/mysql.png")
            .column.is-3.align-center
              img(src="@/assets/img/common/pug.svg")
          .columns.is-mobile
            .column.is-3.align-center
              img(src="@/assets/img/common/node.svg")
            .column.is-3.align-center
              img(src="@/assets/img/common/stylus.svg")
      section.section#links
        .container
          h1.title.raleway LINKS
          h2.subtitle 活動アカウント達
          .contact-links
            h3.is-size-7 Email
            p.is-size-5: a(href="mailto:subayai.kobashiri@gmail.com") subayai.kobashiri@gmail.com
            h3.is-size-7 Twitter
            p.is-size-5: a(href="https://twitter.com/suzuesa") @suzuesa
            h3.is-size-7 Qiita
            p.is-size-5: a(href="https://qiita.com/suzu2469") suzu2469
            h3.is-size-7 github
            p.is-size-5: a(href="https://github.com/suzu2469") suzu2469(ほぼ不使用)
    footer-component
</template>

<script>
import Menu from '@/components/Menu.vue'
import FooterComponent from '@/components/FooterComponent.vue'

export default {
  components: { Menu, FooterComponent }
}
</script>

<style lang="sass" scoped>

.title-logo
  width: 150px
  margin: 0 auto
  display: block

.container > h1.title
  font-weight: 800
  font-size: 3.0rem
  color: black

section.career, section.detail
  margin-top: 3.5rem
  
section.career > h1.title, section.detail > h1.title
  color: black
  margin-bottom: 0.7rem

section.profile-head
  margin-top: 3rem

h2.subtitle
  color: black

p.body
  margin: 1.5rem 0 0
  color: black

.profile-me
  width: 150px
  margin: 0 auto
  img
    width: 100%

.profile-text
  margin: 1.0rem 0
  &:first-of-type
    margin: 2.0rem 0 1.0rem

h3.namefolio
  font-weight: 600

article.work
  .work-image
    max-width: 300px

.skill-icons
  margin-top: 3.0rem

.align-center
  display: flex
  align-items: center

.contact-links
  h3
    margin-top: 1.3rem
  a
    color: #904399
</style>