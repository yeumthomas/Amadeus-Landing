<template>
    <div>
        <!-- SECTION #1: HERO -->
        <section class="section-hero section-shaped my-0">
            <div class="shape shape-style-1 shape-primary">
            </div>
            <div class="ml-lg-8 ml-md-5 ml-4 mr-4 mr-lg-0 mr-md-5 pt-7 shape-container d-flex">
                <div class="row">
                    <div class="col-lg-5 col-md-12 col-xs-12 col-sm-12 px-0 mt-5 pt-5 mr-xs-2 mr-sm-2">
                        <h1 class="display-2  text-secondary display-sm-4" style="font-family: Helvetica Neue">Arrange Virtual Ensembles 
                            with AI.</h1>
                        <p class="lead  text-white">Skip the high fees, long editing time, and complicated 
                            production. Create your virtual ensemble recording with a single click.</p>
                        <div>
                            <badge type="white" class="bg-tertiary" rounded>Customized</badge>
                            <badge type="white" class="bg-tertiary" rounded>Affordable</badge>
                            <badge type="white" class="bg-tertiary" rounded>Quick</badge>
                        </div>
                        <div class="btn-wrapper mt-5 mb-5">
                            <base-button tag="a"
                                            href="https://"
                                            class="mb-3 mb-sm-0"
                                            type="default"
                                            icon="fa fa-edit">
                                Create Now
                            </base-button>
                        </div>
                    </div>         
                    <div class="col-lg-6 text-center mt-5 pt-5 d-xs-none d-lg-inline">
                        <img src="../assets/media/macbook-mockup.png"
                        class="img-fluid pt-4 d-none d-lg-inline">
                    </div>
                </div>
            </div>
        </section>

        <section class="section section-lg">
            <div class="container">
                <div class="row justify-content-center text-center mb-lg">
                    <div class="col-lg-8">
                        <h2 class="display-3">Amadeus was developed by Thomas Yeum</h2>
                        <p class="lead text-muted">According to the National Oceanic and Atmospheric Administration,
                            Ted, Scambos, NSIDClead scentist, puts the potentially record maximum.</p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-1-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Ryan Tompson</span>
                                    <small class="h6 text-muted">Web Developer</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="#" type="warning" icon="fa fa-twitter" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="warning" icon="fa fa-facebook" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="#" type="warning" icon="fa fa-dribbble" rounded
                                                 icon-only></base-button>
                                </div>
                                <div class="row row-grid align-items-center my-md">
                                    <div class="col-lg-6 text-lg-center btn-wrapper">
                                        <a target="_blank" rel="noopener" href="https://twitter.com/creativetim"
                                        class="btn btn-neutral btn-icon-only btn-twitter btn-round btn-lg" data-toggle="tooltip"
                                        data-original-title="Follow us">
                                            <i class="fa fa-twitter"></i>
                                        </a>
                                        <a target="_blank" rel="noopener" href="https://www.facebook.com/creativetim"
                                        class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg" data-toggle="tooltip"
                                        data-original-title="Like us">
                                            <i class="fa fa-facebook-square"></i>
                                        </a>
                                        <a target="_blank" rel="noopener" href="https://dribbble.com/creativetim"
                                        class="btn btn-neutral btn-icon-only btn-dribbble btn-lg btn-round" data-toggle="tooltip"
                                        data-original-title="Follow us">
                                            <i class="fa fa-dribbble"></i>
                                        </a>
                                        <a target="_blank" rel="noopener" href="https://github.com/creativetimofficial"
                                        class="btn btn-neutral btn-icon-only btn-github btn-round btn-lg" data-toggle="tooltip"
                                        data-original-title="Star on Github">
                                            <i class="fa fa-github"></i>
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>            
                </div>
            </div>
        </section>



        <section class="section section-lg pt-0">
            <div class="container">
                <card gradient="tertiary"
                      no-body
                      shadow-size="lg"
                      class="border-0">
                    <div class="p-5">
                        <div class="row align-items-center">
                            <div class="col-lg-8">
                                <h3 class="text-white">We made making virtual ensembles easier for you.</h3>
                                <p class="lead text-white mt-3">I will be the leader of a company that ends up being
                                    worth billions of dollars, because I got the answers. I understand culture.</p>
                            </div>
                            <div class="col-lg-3 ml-lg-auto">
                                <base-button tag="a" href="https://www.creative-tim.com/product/vue-argon-design-system"
                                             type="white" block size="lg">
                                    Register Now
                                </base-button>
                            </div>
                        </div>
                    </div>
                </card>
            </div>
        </section>

    </div>
</template>

<script>
import Images from './components/JavascriptComponents/Images.vue';
export default {
  name: "About",
  components: {Images}
};
</script>
