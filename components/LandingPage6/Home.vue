<template>
  <section id="iq-home" class="iq-banner-12 overview-block-pt blue-bg">
    <div class="container">
      <div class="banner-text text-left">
        <div class="row justify-content-between">
          <div class="col-md-6 align-self-center">
            <h1 class="iq-font-white iq-tw-4">
              Why do we use it <b>Sofbox Template</b>
            </h1>
            <h5 class="iq-font-white iq-mtb-20">
              Lorem Ipsum is simply dummy text
            </h5>
            <form class="form-inline">
              <div class="form-group mb-2">
                <input id="inputPassword2" type="text" class="form-control" placeholder="Search">
              </div>
              <a href="#" class="button bt-black">Search</a>
            </form>
          </div>
          <div class="col-md-6">
            <img class="banner-img img-fluid center-block" :src="require('../../assets/images/bg/21.png')" alt="">
            <img class="banner-phone img-fluid center-block wow fadeInUp" :src="require('../../assets/images/product/mob.png')" alt="">
          </div>
        </div>
      </div>
    </div>
    <div class="banner-objects">
      <span class="banner-objects-01" data-bottom="transform:translatey(50px)" data-top="transform:translatey(-50px);">
        <img :src="require('../../assets/images/drive/03.png')" alt="drive02">
      </span>
      <span class="banner-objects-02 iq-fadebounce">
        <span class="iq-round" />
      </span>
      <span class="banner-objects-03 iq-fadebounce">
        <span class="iq-round" />
      </span>
      <span class="banner-objects-04" data-bottom="transform:translatex(100px)" data-top="transform:translatex(-100px);">
        <img :src="require('../../assets/images/drive/04.png')" alt="drive02">
      </span>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style scoped>

</style>
