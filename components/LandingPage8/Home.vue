<template>
  <div>
    <section id="iq-home" class="iq-banner-02 style-1 overview-block-pt iq-bg-over iq-over-Gradient-top">
      <div class="container">
        <div class="banner-text text-center">
          <div class="row">
            <div class="col-md-12">
              <h1 class=" iq-font-dark iq-tw-8">
                Tecnilog
              </h1>
              <p class="iq-font-dark iq-pt-15 iq-mb-20 iq-plr-100 iq-mlr-100">
                Suministro de Equipos de Proteccion Persolan
              </p>
              <a href="javascript:void(0)" class="button-blue-shadow iq-mt-10 iq-mr-30">Sign up For 30 day Trial</a>
              <a href="javascript:void(0)" class="button-line-shadow iq-mt-10">Buy Now license Here</a>
            </div>
            <div class="col-md-12">
              <img :src="require('../../assets/images/banner/12.png')" class="banner-img img-fluid center-block iq-mt-60" alt="">
            </div>
          </div>
        </div>
        <div class="banner-objects">
          <span class="banner-objects-01 skrollable skrollable-between" data-bottom="transform:translatey(50px)" data-top="transform:translatey(-50px);" style="transform: translateY(8.75706px);">
            <img :src="require('../../assets/images/drive/18.png')" alt="drive02">
          </span>
          <span class="banner-objects-02 iq-fadebounce">
            <span class="iq-round" />
          </span>
          <span class="banner-objects-03 iq-fadebounce">
            <span class="iq-round" />
          </span>
          <span class="banner-objects-04 skrollable skrollable-after" data-bottom="transform:translatex(100px)" data-top="transform:translatex(-100px);" style="transform: translateX(-100px);">
            <img :src="require('../../assets/images/drive/17.png')" alt="drive02">
          </span>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
export default {
  name: 'Home'
}
</script>
