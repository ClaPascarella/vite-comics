<script>

export default {
    data() {
        return {
            links: [
                {
                    text: "CHARACTERS",
                    url: "#home",
                },
                {
                    text: "COMICS",
                    url: "#products",
                },
                {
                    text: "MOVIES",
                    url: "#who",
                },
                {
                    text: "TV",
                    url: "#contacts",
                },
                {
                    text: "GAMES",
                    url: "#contacts",
                },
                {
                    text: "COLLECTIBLES",
                    url: "#contacts",
                },
                {
                    text: "VIDEOS",
                    url: "#contacts",
                },
                {
                    text: "FANS",
                    url: "#contacts",
                },
                {
                    text: "NEWS",
                    url: "#contacts",
                },
                {
                    text: "SHOP",
                    url: "#contacts",
                },
            ],
        }
    }
}

</script>

<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-12 ">
                <header>
                    <div class="d-flex flex-row align-items-center ">

                        <div style="background-size: contain; width: 100px; height: 100px;">
                            <img src="../assets/dc-logo.png" alt="">
                        </div>

                        <div>
                            <a v-for=" link in links" :href="link.url" class="mx-4 text-secondary-emphasis">{{
                                link.text
                                }}</a>
                        </div>

                    </div>

                </header>
            </div>
        </div>

        <div class="row">
            <div class="col-12 bg-dark mt-2">CONTENT GOES HERE</div>
        </div>
    </div>
</template>

<style>
a {
    font-size: 0.8rem;
}
</style>