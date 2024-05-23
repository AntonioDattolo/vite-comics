<script>



</script>

<template>
  <main>
    <section class="container-fluid bg-dark">
        <div class="container d-flex align-items-center justify-content-start">
           <h1 class="col-6 text-center h-25">--> Content Goes Here <--</h1>
        </div>
    </section>


    <section class="container-fluid bg-primary">
        <div class="container d-flex align-items-center justify-content-between">
            <div class="myWidth">
                <img src="../assets/buy-comics-digital-comics.png" alt="">
                <span>
                    DIGITAL COMICS
                </span>
            </div>
            <div class="myWidth">
                <img src="../assets/buy-comics-merchandise.png" alt="">
                <span>
                    DC MERCHANDISE
                </span>
            </div>
            <div class="myWidth">
                <img src="../assets/buy-comics-subscriptions.png" alt="">
                <span>
                    SUBSCRIPTION
                </span>
            </div>
            <div class="myWidth">
                <img src="../assets/buy-comics-shop-locator.png" alt="">
                <span>
                    COMIC SHOP LOCATOR
                </span>
            </div>
            <div class="myWidth">
                <img style="width: 50%;" src="../assets/buy-dc-power-visa.svg" alt="">
                <span>
                    DC POWER VISA
                </span>
            </div>
        </div>
    </section>
  </main>
</template>

<style scoped>
    div{
        height: 280px;
    }
    .myWidth{
        width: calc((100% / 5) - 2rem);
        display: flex;
        align-items: center;
        gap: 1rem;
    }
    img{
        object-fit: contain;
        aspect-ratio: .3;
    }
</style>
