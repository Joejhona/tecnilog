<template>
  <section id="iq-portfolio" class="sofbox-gradient-bg-top">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-8">
          <VTwoSectionTitle :title-section-prop="titleSectionProp" />
        </div>
        <div class="col-lg-12">
          <VTwoCaseStudies :lists="List" />
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: 'Portfolio',
  data () {
    return {
      titleSectionProp: {
        title: 'Featured Works.',
        description: 'If you are planning on developing a product landing app or website, take a look at this beautiful-crafted'
      },

      List: [
        { title: 'Dignissimos wisi cillum', description: 'Wordpress — eCommerce', image: require('../../assets/sofbox-v2/images/home-5/515.jpeg') },
        { title: 'Dignissimos wisi cillum', description: 'Wordpress — eCommerce', image: require('../../assets/sofbox-v2/images/home-5/514.jpeg') },
        { title: 'Dignissimos wisi cillum', description: 'Wordpress — eCommerce', image: require('../../assets/sofbox-v2/images/home-5/513.jpeg') },
        { title: 'Dignissimos wisi cillum', description: 'Wordpress — eCommerce', image: require('../../assets/sofbox-v2/images/home-5/512.jpeg') },
        { title: 'Dignissimos wisi cillum', description: 'Wordpress — eCommerce', image: require('../../assets/sofbox-v2/images/home-5/515.jpeg') }
      ]
    }
  }
}
</script>
<style Scoped>
sofbox-gradient-bg-top {
    background-image: url(../../assets/sofbox-v2/images/home-1/15.png);
    background-position: 0 0 !important;
    background-repeat: no-repeat !important;
}
</style>
