<script>
export default {
  data() {
    return {
        links:
        {
            dcComics: ["Characters", "Comics", "Movies", "TV", "Games", "Videos", "News"],
            shop: ["Shop DC", "Shop DC Collectibles"],
            dc: ["Term Of Use", "Privacy policy(New)", "Ad Choices", "Advertising", "Jobs", "Subscriptions", "Talent Workshops", "CPSC Certificates", "Ratings", "Shop Help", "Contac Us"],
            sites: ["DC", "MAD Magazine", "DC Kids", "DC Universe", "DC Power Visa"]
        }
    }
  },
}

</script>

<template>
    <footer class=" container-fluid myBg">
        <section class="container d-flex justify-content-space-between">

            <!-- sezione con liste -->
            <div class="col-6 d-flex text-decoration-none p-5">
                
                <div class="col-4">
                    <ul>
                        <h3>DC COMICS</h3>
                        <li v-for="element in links.dcComics">{{ element }}</li>
                    </ul>
                    <ul>
                        <h3>SHOP</h3>
                        <li v-for="element in links.shop">{{ element }}</li>
                    </ul>
                </div>
                <div class="col-4">
                    <ul>
                        <h3>DC</h3>
                        <li v-for="element in links.dc">{{ element }}</li>
                    </ul>
                </div>
                <div class="col-4">
                    <ul>
                        <h3>SITES</h3>
                        <li v-for="element in links.sites">{{ element }}</li>
                    </ul>
                </div>
            </div>
            <!-- sezione con immagine -->
            
            <div class="footerBG col-6" src="../assets/dc-logo-bg.png" alt=""></div>
            
        </section>
    </footer>
    <section class="container-fluid bg-dark d-flex align-content-center" style="height: 100px;">
        <div class="container d-flex justify-content-between p-3">
            <div class="col-2 d-flex align-items-center">
                <a class="" href="http://">SIGN UP NOW</a>
            </div>
            <div class="col-6 d-flex align-items-center justify-content-around icon">
                <h5 class="col-4">FOLLOW US</h5>
                <img class="col-1" src="../assets/footer-facebook.png" alt="">
                <img class="col-1" src="../assets/footer-twitter.png" alt="">
                <img class="col-1" src="../assets/footer-youtube.png" alt="">
                <img class="col-1" src="../assets/footer-pinterest.png" alt="">
                <img class="col-1" src="../assets/footer-periscope.png" alt="">

            </div>
        </div>
    </section>
</template>

<style scoped>
 .myBg{
    background-image: url(../assets/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    
 }
.footerBG{
    height: 500px;
    background-image: url(../assets/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
}
li{
    color: grey;
    list-style: none;
}
a{
    text-decoration: none;
    color: rgb(0, 119, 255);
    border: 2px solid rgb(0, 119, 255);;
    font-size: 25px;
    padding:0.5rem;
}
h5{
    color: rgb(0, 119, 255);
    font-weight: bold;
    font-size: 24px;
    white-space: nowrap;
}
</style>
