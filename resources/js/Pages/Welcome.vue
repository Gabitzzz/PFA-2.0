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
    <!--    <Head title="Welcome" />-->
    <Navbar></Navbar>

    <Banner></Banner>

    <Services></Services>

    <Portfolio></Portfolio>

    <About></About>

    <Contact></Contact>

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
