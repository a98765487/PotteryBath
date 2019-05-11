<template lang="pug">
.home
  .texture
  nav.navbar.navbar-expand-lg.navbar-light.fixed-top.navbar-slim
    .container
      a.navbar-brand(href='https://www.facebook.com/toubanyoku.syoutou/' target="_blank")
        img(src='../assets/images/logo.png')
      button.navbar-toggler(type='button', data-toggle='collapse', data-target='#navbarNavAltMarkup', aria-controls='navbarNavAltMarkup', aria-expanded='false', aria-label='Toggle navigation' id="nav-mobile")
        span.navbar-toggler-icon
      #navbarNavAltMarkup.collapse.navbar-collapse
        .navbar-nav.ml-auto
          a.nav-item.nav-link.active(href='#' data-id="section_about_us") 關於我們
          a.nav-item.nav-link(href='#' data-id="section_price") 消費方式
          a.nav-item.nav-link(href='#' data-id="section_view") 店內景觀
          a.nav-item.nav-link(href='#' data-id="section_contact_us") 立即體驗
        .fb-logo
          a(href='https://www.facebook.com/toubanyoku.syoutou/' target="_blank")
            img(src='../assets/images/fb.png')
  header.jumbotron
    .container
        h1(data-0="transform: translateY(-50px)" data-500="transform: translateY(100px)") 湘登陶板浴
        h4(data-0="transform: translateY(-50px)" data-500="transform: translateY(100px)") 當你累了，休息的好去處。
    //- navbar
  main
    section#section_about_us
      .container
        h2.text-center 關於我們
        hr
        .row.my-4
          .col-sm-5(data-0="transform: translateX(-200px)" data-500="transform: translateX(0px)")
            .img
              img.img-fluid(src="../assets/images/ofuro_ganbanyoku.png")
          .col-sm-7.d-flex.align-items-center(data-200="transform: translateX(200px)" data-700="transform: translateX(0px)")
            .text-info
              h3 陶板浴簡介
              p 汗水從體內深層緩慢釋出到20分鐘左右快速流汗從皮脂腺代謝體內毒素等。因細胞活化所排出汗水如同天然的化妝水皮脂膜可以保護肌膚快速衝掃或擦拭身體即可無須沐浴乳。從體內深層持續緩和的讓平時體溫上升改善手腳冰冷體質。活性氣類減少腦波轉α波幫助入眠。病原菌會被除去，腸內益菌會增加身體內部新陳代謝加速且流汗量少時體內毒素由排尿釋出，乳酸被分解痛去除。
        .row.contrast.my-4
          .col-sm-7.d-flex.align-items-center(data-500="transform: translateX(-200px)" data-1000="transform: translateX(0px)")
            .text-info
              h3 會呼吸的牆壁
              p 有「會呼吸的牆壁」之稱的「珪藻磚」可自然調節室內濕氣，比木炭高5000倍的多孔質能長時間淨化空氣。因製造過程加入特殊塗料所以「珪藻磚」亦能釋放出比一般空氣中多3~5倍的負氧離子接近森林浴的空氣品質。陶板浴間全牆使用「珪藻磚」沒有燜熱難耐只有清新舒暢。

          .col-sm-5(data-500="transform: translateX(200px)" data-1000="transform: translateX(0px)")
            .img
              img.img-fluid(src="../assets/images/kafun_sukkiri_woman.png")
        .row.my-4
          .col-sm-5(data-700="transform: translateX(-200px)" data-1200="transform: translateX(0px)")
            .img
                img.img-fluid(src="../assets/images/drink_water_boy2.png")
          .col-sm-7.d-flex.align-items-center(data-700="transform: translateX(200px)" data-1200="transform: translateX(0px)")
            .text-info
              h3 癌細胞怕熱
              p 日本石原結實醫師認為，癌 症是因免疫力下降而形成，且 與血液有關連，也就是說它的 發生與血液循環不佳有密切關 係。 身體為了燃燒並排出體內的 廢物，產生發燒現象。所以提升 體溫可以使免疫力提升，並抑制 癌細胞生長！ 一旦身體冰冷，血液循環變 差，體內細胞的代謝也會變 差！體溫每下降 1 度，代謝就 會減少約 12％，免疫力也會降 低 30％。當人體體溫降至 35 度 時，正是癌細胞最活躍繁殖的時 候，反之，當體溫達到 39.6 度 以上時，癌細胞就會全部被殺死。
    section#section_price.bg.pb-4
      .container
        .row.justify-content-center.py-4
        h2.text-center 消費方式
        .row
          .col-sm-12(data-1700="opacity: 0" data-2000="opacity: 1")
            table.table
              thead
                tr
                  th(scope='col') 票卷數量(張)
                  th(scope='col') 價錢
              tbody
                tr
                  th(scope='row') 1
                  td $480
                tr
                  th(scope='row') 10
                  td $4000
                tr
                  th(scope='row') 20
                  td $7000
                tr
                  th(scope='row') 30
                  td $10000
                tr
                  th(scope='row') 8天使用5次
                  td $1500
                tr
                  th(scope='row') 30日天天使用
                  td $5000
            ul.text-notice.mt-3
              li 優惠卷一本為10張，使用期限為一年。
              li 多一人共用+$1000。
    section#section_view.my-5
      .container
        h2.text-center 店內景觀
        hr
        .slick.slider-for
          figure.figure
            img.figure-img.img-fluid.rounded.mx-auto(src='../assets/images/slider1.jpg', alt='')
          figure.figure
            img.figure-img.img-fluid.rounded.mx-auto(src='../assets/images/slider2.jpg', alt='')
          figure.figure
            img.figure-img.img-fluid.rounded.mx-auto(src='../assets/images/slider3.jpg', alt='')
          figure.figure
            img.figure-img.img-fluid.rounded.mx-auto(src='../assets/images/slider5.jpg', alt='')
          figure.figure
            img.figure-img.img-fluid.rounded.mx-auto(src='../assets/images/slider6.jpg', alt='')
          figure.figure
            img.figure-img.img-fluid.rounded.mx-auto(src='../assets/images/slider7.jpg', alt='')
        .slick.slider-nav
          figure.figure
            img.figure-img.img-fluid.rounded.mx-auto(src='../assets/images/slider1.jpg', alt='')
          figure.figure
            img.figure-img.img-fluid.rounded.mx-auto(src='../assets/images/slider2.jpg', alt='')
          figure.figure
            img.figure-img.img-fluid.rounded.mx-auto(src='../assets/images/slider3.jpg', alt='')
          figure.figure
            img.figure-img.img-fluid.rounded.mx-auto(src='../assets/images/slider5.jpg', alt='')
          figure.figure
            img.figure-img.img-fluid.rounded.mx-auto(src='../assets/images/slider6.jpg', alt='')
          figure.figure
            img.figure-img.img-fluid.rounded.mx-auto(src='../assets/images/slider7.jpg', alt='')
    section#section_contact_us.mt-3
      .container
        h2.text-center 聯絡管道
        hr
        .row
          .col-md-6
            .contact_text_info.p-4.my-4
              .row
                .col-sm-6
                  h4 聯絡方式：
                  ul.mt-2
                    li
                      a(href="tel:+886-2-3278918") (02)2967-8499
                  h4 營業時間：
                  ul.mt-2
                    li 週一周日公休
                    li 週二至週五 10:00 至 18:00
                    li 週三 10:00 至 20:30
                    li 週六採
                      span.text-danger 預約制
                      |  11:00 至 18:30
                  h4 交通資訊：
                  ul.mt-2
                    li 捷運-板橋站一號出口 步行約12分
                    li 公車-大庭新村站 步行約1分
                .col-sm-6
                  img.img-fluid(src='../assets/images/2019-04-27_141111.png')
          .col-md-6
            .gmap#map.my-4
  footer.text-center
    p 湘登陶板浴版權所有 © 2019 All Rights Reserved.
</template>

<script>
/* eslint-disable */
// import Navbar from '@/components/Navbar.vue'

export default {
  name: 'home',
  // components: {
  //   Navbar
  // },
  mounted: function() {
    // google map api
    initMap();
    // slider
    $('.slider-for').slick({
      slidesToShow: 1,
      slidesToScroll: 1,
      autoplay:true,
      arrows: false,
      fade: true,
      asNavFor: '.slider-nav',
      centerMode: true,
      focusOnSelect: false,
      pauseOnHover:false,
      pauseOnFocus:false
    });
    $('.slider-nav').slick({
      slidesToShow: 5,
      slidesToScroll: 1,
      arrows: false,
      asNavFor: '.slider-for',
      dots: false,
      centerMode: true,
      focusOnSelect: true,
    });
    //nav click
    $("#navbarNavAltMarkup>.navbar-nav a").click(function(e){
      e.preventDefault()
      $("#navbarNavAltMarkup a").removeClass("active")
      $(this).addClass("active")
      let pos = $("#" + $(this).data("id")).offset().top
      $('html,body').animate({scrollTop: pos - 100}, 500);
      //手機板
      $("#navbarNavAltMarkup").removeClass("show")
    })
    //skrollr
    if(!this.isMobile())
    var s = skrollr.init()

  },
  methods:{
    isMobile : function(){
        try{ document.createEvent("TouchEvent"); return true; }
        catch(e){ return false;}
    }
  }
}
</script>
