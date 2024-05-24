<script>

export default {
    data() {
        return {
            links: [
                {
                    text: "Home",
                    url: "#home",
                },
                {
                    text: "Prodotti",
                    url: "#products",
                },
                {
                    text: "Chi Siamo",
                    url: "#who",
                },
                {
                    text: "Contatti",
                    url: "#contacts",
                },
            ],
        }
    }
}

</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col-12 ">
                <header>
                    <a v-for=" link in links" :href="link.url">{{ link.text }}</a>
                </header>
            </div>
        </div>
    </div>
</template>

<style></style>