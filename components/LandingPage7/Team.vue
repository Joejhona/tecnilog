<template>
    <div>
        <section id="team" class="overview-block-ptb white-bg">
            <div class="container">
                <div class="row">
                <div class="col-sm-12">
                    <div class="heading-title">
                    <h3 class="title iq-tw-7">Meet the Team</h3>
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p>
                    </div>
                </div>
                </div>
                <div class="row">
                <div class="col-sm-12 col-lg-3 col-md-6" v-for="(item, index) of list" :key="index">
                    <CardStyle8>
                    <img slot="cardMedia" :src="item.image" class="img-fluid center-block" alt="#">
                    <div slot="cardHeader">
                        <h5 class="iq-font-black iq-tw-7">{{ item.title }}</h5>
                        <span class="team-post">{{ item.subtitle }}</span>
                    </div>
                    <div slot="cardOverlay">
                        <ul>
                        <li><a href="javascript:void(0)"><i class="fab fa-twitter"></i></a></li>
                        <li><a href="javascript:void(0)"><i class="fab fa-facebook"></i></a></li>
                        <li><a href="javascript:void(0)"><i class="fab fa-google"></i></a></li>
                        <li><a href="javascript:void(0)"><i class="fab fa-github"></i></a></li>
                        </ul>
                    </div>
                    </CardStyle8>
                </div>
                </div>
            </div>
        </section>
    </div>
</template>
<script>
export default {
    name:'Team',
    data(){
        return{
            list: [
                    {
                        title: 'JD Adams',
                        subtitle: 'Web Designer',
                        image: require('../../assets/images/team/01.png')
                    },
                    {
                        title: 'Rinkal Oberoi',
                        subtitle: 'Web Designer',
                        image: require('../../assets/images/team/02.png')
                    },
                    {
                        title: 'Jason Deol',
                        subtitle: 'Web Designer',
                        image: require('../../assets/images/team/03.png')
                    },
                    {
                        title: 'kush Jackson',
                        subtitle: 'Web Designer',
                        image: require('../../assets/images/team/04.png')
                    }
            ]
        }
    }
}
</script>