<template>
  <section id="team" class="iq-team pt-0">
    <div class="container">
      <div class="row">
        <div class="col-sm-12">
          <BlackSectionTitle title="Team" subtitle="Our Team" />
        </div>
      </div>
      <div class="row">
        <div class="col-lg-6">
          <BlackCardStyle3 v-for="(team,index) in teams" :key="index" :class-name="team.class" :right="false">
            <template v-slot:cardMedia>
              <div class="team-img">
                <img :src="team.src" class="img-fluid" alt="images">
              </div>
            </template>
            <template v-slot:cardContent>
              <h5 class="mb-3">
                Nik Jorden
              </h5>
              <p class="mb-3">
                There are many variations of passages of Lorem Ipsum available, but the
              </p>
              <ul class="social-media">
                <li><a href="#"><i class="fab fa-facebook-f" /></a></li>
                <li><a href="#"><i class="fab fa-google-plus-g" /></a></li>
                <li><a href="#"><i class="fab fa-twitter" /></a></li>
              </ul>
            </template>
          </BlackCardStyle3>
        </div>
        <div class="col-lg-6">
          <BlackCardStyle3 class-name="wow slideInUp">
            <template v-slot:cardMedia>
              <div class="team-img">
                <img src="../../assets/sofbox-sass-black/images/team/03.jpg" class="img-fluid" alt="images">
              </div>
            </template>
            <template v-slot:cardContent>
              <h5 class="mb-3">
                Nik Jorden
              </h5>
              <p class="mb-3">
                There are many variations of passages of Lorem Ipsum available, but the
              </p>
              <ul class="social-media">
                <li><a href="#"><i class="fab fa-facebook-f" /></a></li>
                <li><a href="#"><i class="fab fa-google-plus-g" /></a></li>
                <li><a href="#"><i class="fab fa-twitter" /></a></li>
              </ul>
            </template>
          </BlackCardStyle3>
          <BlackCardStyle3 class-name="wow slideInUp mb-0" :right="false">
            <template v-slot:cardMedia>
              <div class="team-img">
                <img src="../../assets/sofbox-sass-black/images/team/04.jpg" class="img-fluid" alt="images">
              </div>
            </template>
            <template v-slot:cardContent>
              <h5 class="mb-3">
                Nik Jorden
              </h5>
              <p class="mb-3">
                There are many variations of passages of Lorem Ipsum available, but the
              </p>
              <ul class="social-media">
                <li><a href="#"><i class="fab fa-facebook-f" /></a></li>
                <li><a href="#"><i class="fab fa-google-plus-g" /></a></li>
                <li><a href="#"><i class="fab fa-twitter" /></a></li>
              </ul>
            </template>
          </BlackCardStyle3>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: 'Team',
  data () {
    return {
      teams: [
        {
          class: 'wow slideInUp',
          src: require('../../assets/sofbox-sass-black/images/team/01.jpg')
        },
        {
          class: 'wow slideInUp mb-0',
          src: require('../../assets/sofbox-sass-black/images/team/02.jpg')
        }
      ]
    }
  }
}
</script>
