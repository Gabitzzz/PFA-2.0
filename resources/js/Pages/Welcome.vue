<script setup>
import {Head, Link} from '@inertiajs/inertia-vue3';


defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
})

</script>

<template>
    <Navbar></Navbar>

    <div class="w-full px-4 py-8  sm:px-8 md:px-16 lg:px-24 xl:px-40 pt-24 md:pt-40">
        <section id="banner">
            <Banner></Banner>
        </section>

        <Services></Services>

        <section id="portfolio" class="pt-32">
            <Portfolio></Portfolio>
        </section>

        <section id="about" class="pt-16">
            <About></About>
        </section>

        <section id="contact">
            <Contact></Contact>
        </section>
    </div>

    <Footer></Footer>


</template>
<script>
import Navbar from "@/Components/Navbar";
import Portfolio from "@/Components/Portfolio";
import About from "@/Components/About";

import Footer from "@/Components/Footer";
import Banner from "@/Components/Banner";
import Services from "@/Components/Services";
import Contact from "@/Components/Contact";

export default {
    data() {
        return {
            // gif: gif,
        }
    },
    components: {
        Navbar,
        Footer,
        Banner,
        Services,
        Portfolio,
        About,
        Contact,
    }
}
</script>

<style scoped>


/* For demonstration purposes only: */
</style>
