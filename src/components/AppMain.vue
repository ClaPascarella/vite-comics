<script>
import ComicsList from "./ComicsList.vue";

export default {
    components: {
        ComicsList,
    },

}
</script>

<template>
    <!-------CONTAINER JUMBO---------->
    <div class="mt-2">
        <img src="../assets/jumbotron.jpg" alt="" style="width: 100%; height: 30rem; background-size: contain;">
    </div>

    <!-------CONTAINER FUMETTI-------->
    <div class="container-fluid">
        <div class="row">
            <div class="col-12 bg-dark text-white">
                <div class="container" style="width: 1000px;">
                    <div class="col-2 d-flex flex-row align-items-center justify-content-center">
                        <ComicsList />
                    </div>

                </div>

            </div>
        </div>
    </div>

    <!-------- CONTAINER PRIMARY------>
    <div class="bg-primary d-flex flex-row justify-content-around" style="max-width: 100%; height: 10rem;">

        <div class="d-flex flex-row align-items-center">
            <img src="../assets/buy-comics-digital-comics.png" alt="" style="width: 60px; height: 60px;">
            <p class="text-white ms-2">DIGITAL COMICS</p>
        </div>

        <div class="d-flex flex-row align-items-center">
            <img src="../assets/buy-comics-merchandise.png" alt="" style="width: 60px; height: 60px;">
            <p class="text-white ms-2 ">DC MERCHANDISE</p>
        </div>

        <div class="d-flex flex-row align-items-center">
            <img src="../assets/buy-comics-subscriptions.png" alt="" style="width: 60px; height: 60px;">
            <p class="text-white ms-2">SUBSCRIPTION</p>
        </div>

        <div class="d-flex flex-row align-items-center">
            <img src="../assets/buy-comics-shop-locator.png" alt="" style="width: 60px; height: 60px;">
            <p class="text-white ms-2">COMIC SHOP LOCATOR</p>
        </div>

        <div class="d-flex flex-row align-items-center">
            <img src="../assets/buy-dc-power-visa.svg" alt="" style="width: 60px; height: 60px;">
            <p class="text-white ms-2">DC POWER VISA</p>
        </div>

    </div>


</template>