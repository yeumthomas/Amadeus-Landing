<template>
    <div>
        <!-- SECTION #1: HERO -->
        <section class="section-hero section-shaped my-0">
            <div class="shape shape-style-1 shape-primary">
            </div>
            <div class="ml-lg-8 ml-md-5 ml-4 mr-4 mr-lg-0 mr-md-5 pt-9 shape-container d-flex">
                <div class="row">
                    <div class="col-lg-5 col-md-12 col-xs-12 col-sm-12 px-0 mt-6 pt-5 mr-xs-2 mr-sm-2 mr-md-6">
                        <h1 class="display-2  text-secondary display-sm-4" 
                            style="font-family: Helvetica Neue">Contact Us for Rates & Registration</h1>
                        <p class="lead  text-white">Amadeus racks up a bit of storage costs, so to 
                            keep this service running we do charge a fee.</p>
                        <p class="font-weight-bold text-white">This service is completely free to students and to all 
                            KatyISD orchestra, band, and choir directors.</p>
                    </div>         
                    <div class="col-lg-6 text-center mt-5 pt-4 mb-5"> 
                        <div class='row'>
                            <div class="col text-center">
                                <img src="../../public/email.svg"
                                class="img-fluid"
                                style="width: 23rem">
                            </div>
                        </div>
                        <div class='row'>
                            <div class="col text-center"
                                style="margin-top: -5rem;">
                                <base-button tag="a"
                                    type="default" 
                                    class=""
                                    icon="ni ni-send"
                                    href="mailto:my.amadeusvideo@gmail.com"
                                    >Send an Email
                                </base-button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    
    </div>
</template>

<script>
export default {
  name: "Pricing",
  data () {
      return{
          name: '',
          email: '',
          subject: '',
          body: ''
      }
  },
  methods: {
      async sendIt() {

      }
  }
};
</script>
