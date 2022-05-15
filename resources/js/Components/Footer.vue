<template>
    <nav id="footer" class="bg-footer px-8 md:px-24 lg:px-40 2xl:px-80 pt-2">
        <!-- start container -->
        <div class="container items-center grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-10 content-center ">

            <div class="  flex-wrap overflow-hidden sm:-mx-1 md:-mx-px lg:-mx-2 xl:-mx-2">
                <img :src="logo"
                     alt=""
                     class="w-24 md:w-36 "
                     style=" filter:  brightness(0) invert(1);"
                >

                <p class="mt-4">
                    Lițcan Nicolae-Gabriel PFA is a Web Design & Development company that deals with the creation of
                    websites, online stores, SEO and Social Media Promotion.
                </p>
            </div>

            <div class="pt-6">
                <!-- Column 2 Content -->
                <ul class="  "
                    style="font-family: 'Poppins', sans-serif; font-weight: normal;">
                    <li><a class=" rounded-full underline-opening" href="#banner">HOME</a></li>
                    <li><a class=" rounded-full underline-opening" href="#portfolio">PORTFOLIO</a></li>
                    <li><a class=" rounded-full underline-opening" href="#about">ABOUT ME</a></li>
                    <li><a class=" rounded-full underline-opening" href="#contact">CONTACT</a></li>
                </ul>
            </div>

            <div class="pt-6">
                <!-- Column 2 Content -->
                <ul class="  "
                    style="font-family: 'Poppins', sans-serif; font-weight: normal;">
                    <li><a class=" rounded-full underline-opening" href="https://goo.gl/maps/MDxLQff43DTB3WJ98">
                        Brănești,
                        Ilfov, România</a></li>
                    <li><a class=" rounded-full underline-opening" href="mailto:litcangabi@gmail.com">litcangabi@gmail.com</a>
                    </li>
                    <li><a class=" rounded-full underline-opening" href="tel:+40773800815">0773 800 815</a></li>
                </ul>
            </div>
        </div>

        <div class="pt-4 md:flex md:items-center md:justify-center ">
            <div class="footer-copyright text-white-50 py-3" style="color:white;">© 2021-2022 Lițcan
                Nicolae-Gabriel PFA.
                All rights reserved
            </div>
        </div>


    </nav>
</template>

<script>
import logo from "/images/logo2.png";

export default {
    name: "Footer",
    data() {
        return {
            logo: logo,
        }
    }
}
</script>

<style scoped>
.bg-footer {
    background-color: #191D24;
}
</style>
