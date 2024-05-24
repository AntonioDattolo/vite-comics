<script>

import AppMainChildJumbtron from './AppMainChildJumbtron.vue';

export default {
  components: {
   AppMainChildJumbtron,
  },
  data() {
    return {

    }
  }
  // methods: {
  //   ///
  // },
  // mounted: {

  // }
}


</script>

<template>
  <main>
    <section class="container-fluid bg-dark myHeigth">
        <AppMainChildJumbtron />
        <div class="container d-flex align-items-center justify-content-start">
           dsadasd
        </div>
    </section>


    <section class="container-fluid bg-primary h-50">
        <div class="container d-flex align-items-center flex-wrap py-5 justify-content-between">
            <div class="col-sm-6 col-md-6 col-lg-2 col-xl-2 offset-xl-0 p-lg-0 d-flex">
                <div class="myCardImg col-12">
                    <img  src="../assets/buy-comics-digital-comics.png" alt="">
                    <h6 class="d-inline px-1">
                        DIGITAL COMICS
                    </h6>
                
                </div>
            </div>
            <div class="col-sm-6 col-md-6 col-lg-2 col-xl-2 offset-xl-0 p-2 p-lg-0 d-flex">
                <div class="myCardImg col-12">
                    <img  src="../assets/buy-comics-merchandise.png" alt="">
                    <h6 class="d-inline px-1">
                        DC MERCHANDISE
                    </h6>
                
                </div>
            </div>
            <div class="col-sm-6 col-md-6 col-lg-2 col-xl-2 offset-xl-0 p-2 p-lg-0 d-flex">
                <div class="myCardImg col-12">
                    <img  src="../assets/buy-comics-subscriptions.png" alt="">
                    <h6 class="d-inline px-1">
                        SUBSCRIPTION
                    </h6>
                
                </div>
            </div>
            <div class="col-sm-6 col-md-6 col-lg-2 col-xl-2 offset-xl-0 p-2 p-lg-0 d-flex">
                <div class="myCardImg col-12">
                    <img  src="../assets/buy-comics-shop-locator.png" alt="">
                    <h6 class="d-inline px-1">
                        COMIC SHOP LOCATOR
                    </h6>
                
                </div>
            </div>
            <div class="col-sm-6 offset-sm-3 col-md-6 offset-md-3 col-lg-2 offset-lg-0 col-xl-2 offset-xl-0 d-flex">
                <div class="myCardImg col-12">
                    <img style="width: 90px;" src="../assets/buy-dc-power-visa.svg" alt="">
                    <h6 class="d-inline px-1">
                        DC POWER VISA
                    </h6>
                
                </div>
            </div>
        </div>
    </section>
  </main>
</template>

<style scoped>
    /* .myHeigth{
        height: 200px;
    } */
    img{
        object-fit: contain;
        height: 50%;
    }
    div{
        font-size: 15px;
        
        white-space-collapse: collapse;
    }
    h6{
        font-size: 12px;
    }
    .myCardImg{
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>
