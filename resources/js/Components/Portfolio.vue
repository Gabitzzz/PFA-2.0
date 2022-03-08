<template>
    <div class="w-full px-8 md:px-16 lg:px-24 xl:px-40 pb-24 mt-32 ">
        <p
            class="text-6xl text-center"
            style="font-family: 'Poppins', sans-serif; font-weight:bold;">
            Portfolio
        </p>


        <!--        <img :src="ted" alt="Gif" width="550"/>-->

        <p
            class="text-3xl mt-8 "
            style="font-family: 'Poppins', sans-serif; font-weight:bold;">
            Clients
        </p>
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-10 content-center mt-16">


            <!--            FIRST ROW  -->
            <div class="content ">
                <a href="https://www.tedxuniversityofessex.com/">
                    <div class="content-overlay"></div>
                    <img :src="ted" alt="Gif" width="550" class=""/>
                    <div class="content-details fadeIn-bottom">
                        <h5 style="color: white;">TED<sup>x</sup>UniversityOfEssex</h5>
                        <p class="content-text">Web Design & Development</p>
                        <p class="content-text">WIX</p>
                    </div>
                </a>
            </div>
            <div class="content ">
                <a href="https://www.tedxuniversityofessex.com/">
                    <div class="content-overlay"></div>
                    <img :src="ted" alt="Gif" width="550" class=""/>
                    <div class="content-details fadeIn-bottom">
                        <h5 style="color: white;">TED<sup>x</sup>UniversityOfEssex</h5>
                        <p class="content-text">Web Design & Development</p>
                        <p class="content-text">WIX</p>
                    </div>
                </a>
            </div>
            <div class="content ">
                <a href="https://www.tedxuniversityofessex.com/">
                    <div class="content-overlay"></div>
                    <img :src="ted" alt="Gif" width="550" class=""/>
                    <div class="content-details fadeIn-bottom">
                        <h5 style="color: white;">TED<sup>x</sup>UniversityOfEssex</h5>
                        <p class="content-text">Web Design & Development</p>
                        <p class="content-text">WIX</p>
                    </div>
                </a>
            </div>
            <div class="content ">
                <a href="https://www.tedxuniversityofessex.com/">
                    <div class="content-overlay"></div>
                    <img :src="ted" alt="Gif" width="550" class=""/>
                    <div class="content-details fadeIn-bottom">
                        <h5 style="color: white;">TED<sup>x</sup>UniversityOfEssex</h5>
                        <p class="content-text">Web Design & Development</p>
                        <p class="content-text">WIX</p>
                    </div>
                </a>
            </div>

            <!--            SECOND ROW      -->
            <div class="content ">
                <a href="https://www.tedxuniversityofessex.com/">
                    <div class="content-overlay"></div>
                    <img :src="ted" alt="Gif" width="550" class=""/>
                    <div class="content-details fadeIn-bottom">
                        <h5 style="color: white;">TED<sup>x</sup>UniversityOfEssex</h5>
                        <p class="content-text">Web Design & Development</p>
                        <p class="content-text">WIX</p>
                    </div>
                </a>
            </div>
            <div class="content ">
                <a href="https://www.tedxuniversityofessex.com/">
                    <div class="content-overlay"></div>
                    <img :src="ted" alt="Gif" width="550" class=""/>
                    <div class="content-details fadeIn-bottom">
                        <h5 style="color: white;">TED<sup>x</sup>UniversityOfEssex</h5>
                        <p class="content-text">Web Design & Development</p>
                        <p class="content-text">WIX</p>
                    </div>
                </a>
            </div>
            <div class="content ">
                <a href="https://www.tedxuniversityofessex.com/">
                    <div class="content-overlay"></div>
                    <img :src="ted" alt="Gif" width="550" class=""/>
                    <div class="content-details fadeIn-bottom">
                        <h5 style="color: white;">TED<sup>x</sup>UniversityOfEssex</h5>
                        <p class="content-text">Web Design & Development</p>
                        <p class="content-text">WIX</p>
                    </div>
                </a>
            </div>
            <div class="content ">
                <a href="https://www.tedxuniversityofessex.com/">
                    <div class="content-overlay"></div>
                    <img :src="ted" alt="Gif" width="550" class=""/>
                    <div class="content-details fadeIn-bottom">
                        <h5 style="color: white;">TED<sup>x</sup>UniversityOfEssex</h5>
                        <p class="content-text">Web Design & Development</p>
                        <p class="content-text">WIX</p>
                    </div>
                </a>
            </div>
        </div>

        <div class="flex items-center  ">
            <div class="content pt-8 " style="margin: initial !important;">
                <a href="https://www.tedxuniversityofessex.com/">
                    <div class="content-overlay"></div>
                    <img :src="esn" alt="Gif" width="550" class=""/>
                    <div class="content-details fadeIn-bottom">
                        <h5 style="color: white;">TED<sup>x</sup>UniversityOfEssex</h5>
                        <p class="content-text">Web Design & Development</p>
                        <p class="content-text">WIX</p>
                    </div>
                </a>
            </div>
            <div>
                <p
                    class="text-5xl"
                    style="font-family: 'Poppins', sans-serif; font-weight:bold;">
                    Essex Social Network
                    <br>
                </p>

                <p class="mt-4">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi aspernatur consequuntur deserunt,
                    doloribus dolorum et, exercitationem hic minus obcaecati optio placeat quae, quisquam quod quos
                    recusandae saepe sunt temporibus veritatis?
                </p>
            </div>

        </div>


    </div>
</template>

<script>


import ted from "/images/ted.webp";
import esn from "/images/mockup.png";
import {Swiper, SwiperSlide} from 'swiper/vue';
import 'swiper/css';


export default {
    name: "Portfolio",
    data() {
        return {
            ted: ted,
            esn: esn,
        }
    },

}
</script>

<style scoped>
.content {
    position: relative;
    width: 90%;
    max-width: 400px;
    margin: auto;
    overflow: hidden
}

.content .content-overlay {
    background: rgba(0, 0, 0, 0.7);
    position: absolute;
    height: 99%;
    width: 100%;
    left: 0;
    top: 0;
    bottom: 0;
    right: 0;
    opacity: 0;
    -webkit-transition: all 0.4s ease-in-out 0s;
    -moz-transition: all 0.4s ease-in-out 0s;
    transition: all 0.4s ease-in-out 0s
}

.content:hover .content-overlay {
    opacity: 1
}

.content-image {
    width: 100%
}

img {
    /*box-shadow: 1px 1px 5px 1px rgba(0, 0, 0, 0.1);*/
    border-radius: 5px
}

.content-details {
    position: absolute;
    text-align: center;
    padding-left: 1em;
    padding-right: 1em;
    width: 100%;
    top: 50%;
    left: 50%;
    opacity: 0;
    -webkit-transform: translate(-50%, -50%);
    -moz-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    -webkit-transition: all 0.3s ease-in-out 0s;
    -moz-transition: all 0.3s ease-in-out 0s;
    transition: all 0.3s ease-in-out 0s
}

.content:hover .content-details {
    top: 50%;
    left: 50%;
    opacity: 1
}

.content-details h3 {
    color: #fff;
    font-weight: 500;
    letter-spacing: 0.15em;
    margin-bottom: 0.5em;
    text-transform: uppercase
}

.content-details p {
    color: #fff;
    font-size: 0.8em
}

.fadeIn-bottom {
    top: 80%
}

.collapse-arrow .collapse-title:after {
    position: relative !important;
    right: 0 !important;
}

.collapse-title, .collapse > input[type="checkbox"] {
    padding-right: 0 !important;
}
</style>
