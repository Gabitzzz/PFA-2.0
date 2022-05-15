<template>
    <!--    <div class="w-full px-8 md:px-16 lg:px-24 xl:px-40 pb-24 mt-32 ">-->
    <p
        class="text-4xl sm:text-6xl text-center"
        style="font-family: 'Poppins', sans-serif; font-weight:bold;">
        Portfolio
    </p>


    <!--        <img :src="ted" alt="Gif" width="550"/>-->

    <p
        class="text-4xl mt-8 "
        style="font-family: 'Poppins', sans-serif; font-weight:bold;">
        Clients
    </p>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-10 content-center mt-8">


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
            <a href="https://vin-cadou.ro//">
                <div class="content-overlay"></div>
                <img :src="dws" alt="Gif" width="550" class=""/>
                <div class="content-details fadeIn-bottom">
                    <h5 style="color: white;">Dream Wine Special</h5>
                    <p class="content-text">Web Design & Development, LOGO, SEO</p>
                    <p class="content-text">WordPress</p>
                </div>
            </a>
        </div>
        <div class="content ">
            <a href="https://taraluipatratel.ro//">
                <div class="content-overlay"></div>
                <img :src="patratel" alt="Gif" width="550" class=""/>
                <div class="content-details fadeIn-bottom">
                    <h5 style="color: white;">Țara lui Pătrățel</h5>
                    <p class="content-text">Web Design & Development, Graphic Design</p>
                    <p class="content-text">WordPress</p>
                </div>
            </a>
        </div>
        <div class="content ">
            <a href="https://arhique.ro//">
                <div class="content-overlay"></div>
                <img :src="arhique" alt="Gif" width="550" class=""/>
                <div class="content-details fadeIn-bottom">
                    <h5 style="color: white;">Arhique</h5>
                    <p class="content-text">Web Design & Development</p>
                    <p class="content-text">Laravel</p>
                </div>
            </a>
        </div>

        <!--                        SECOND ROW      -->
        <!--            <div class="content ">-->
        <!--                <a href="https://www.tedxuniversityofessex.com/">-->
        <!--                    <div class="content-overlay"></div>-->
        <!--                    <img :src="ted" alt="Gif" width="550" class=""/>-->
        <!--                    <div class="content-details fadeIn-bottom">-->
        <!--                        <h5 style="color: white;">TED<sup>x</sup>UniversityOfEssex</h5>-->
        <!--                        <p class="content-text">Web Design & Development</p>-->
        <!--                        <p class="content-text">WIX</p>-->
        <!--                    </div>-->
        <!--                </a>-->
        <!--            </div>-->
        <!--            <div class="content ">-->
        <!--                <a href="https://www.tedxuniversityofessex.com/">-->
        <!--                    <div class="content-overlay"></div>-->
        <!--                    <img :src="ted" alt="Gif" width="550" class=""/>-->
        <!--                    <div class="content-details fadeIn-bottom">-->
        <!--                        <h5 style="color: white;">TED<sup>x</sup>UniversityOfEssex</h5>-->
        <!--                        <p class="content-text">Web Design & Development</p>-->
        <!--                        <p class="content-text">WIX</p>-->
        <!--                    </div>-->
        <!--                </a>-->
        <!--            </div>-->
        <!--            <div class="content ">-->
        <!--                <a href="https://www.tedxuniversityofessex.com/">-->
        <!--                    <div class="content-overlay"></div>-->
        <!--                    <img :src="ted" alt="Gif" width="550" class=""/>-->
        <!--                    <div class="content-details fadeIn-bottom">-->
        <!--                        <h5 style="color: white;">TED<sup>x</sup>UniversityOfEssex</h5>-->
        <!--                        <p class="content-text">Web Design & Development</p>-->
        <!--                        <p class="content-text">WIX</p>-->
        <!--                    </div>-->
        <!--                </a>-->
        <!--            </div>-->
        <!--            <div class="content ">-->
        <!--                <a href="https://www.tedxuniversityofessex.com/">-->
        <!--                    <div class="content-overlay"></div>-->
        <!--                    <img :src="ted" alt="Gif" width="550" class=""/>-->
        <!--                    <div class="content-details fadeIn-bottom">-->
        <!--                        <h5 style="color: white;">TED<sup>x</sup>UniversityOfEssex</h5>-->
        <!--                        <p class="content-text">Web Design & Development</p>-->
        <!--                        <p class="content-text">WIX</p>-->
        <!--                    </div>-->
        <!--                </a>-->
        <!--            </div>-->
    </div>

    <p
        class="text-4xl mt-16 "
        style="font-family: 'Poppins', sans-serif; font-weight:bold;">
        Capstone Project
    </p>

    <p
        class="text-md mt-4 "
        style="font-family: 'Poppins', sans-serif;">
        <!--        Here is my favourite Tech Stack, languages and frameworks that I use every day in most of my projects.-->
        Capstone Project at University of Essex is an Assignment that serves as a culminating academic and intellectual
        experience for undergraduate students in their final year.. They can choose a project from University's database
        or come up with their own project. Capstone Project is 25% of the Undergraduate Degree.
    </p>


    <div class="md:flex items-center  ">
        <div class="  " style="margin: initial !important;">
            <a href="https://essex.social">
                <div class="content-overlay"></div>
                <img :src="esn" alt="Gif" class="w-full px-6"/>
            </a>
        </div>

        <div>
            <a href="https://essex.social/">
                <p
                    class="mt-4 sm:mt-0 text-2xl lg:text-2xl"
                    style="font-family: 'Poppins', sans-serif; font-weight:bold;">
                    Essex Social Network
                    <br>
                </p>
            </a>

            <p class="mt-4">
                Essex Social Network is an exclusive Social Media Platform destined to be used by people from within
                University of Essex. Built to enhance student’s experience, it combines the traditional elements of a
                Social Media App with the University of Essex’s Online Platforms, helping students with their academic
                and social life.
            </p>

            <a href="https://essex.social/">
                <p
                    class="text-xl mt-4"
                    style="font-family: 'Poppins', sans-serif; font-weight:bold;">
                    essex.social
                </p>
            </a>

        </div>

    </div>

    <div class="md:flex items-center mt-16 ">


        <div class="md:w-1/2">
            <p
                class="mt-4 sm:mt-0 text-4xl lg:text-4xl"
                style="font-family: 'Poppins', sans-serif; font-weight:bold;">
                Other Projects
                <br>
            </p>

            <p class="mt-4">
                <!--                Essex Social Network is an exclusive Social Media Platform destined to be used by people from within-->
                <!--                University of Essex. Built to enhance student’s experience, it combines the traditional elements of a-->
                <!--                Social Media App with the University of Essex’s Online Platforms, helping students with their academic-->
                <!--                and social life.-->

                Check out other projects, inlucding <br>

            </p>

            <ul>
                <li>
                    • House Price Prediction
                </li>
                <li>
                    • 2D Sliding-Puzzle Solver
                </li>
                <li>
                    • Analysis and Forecasting Program
                </li>
                <li>
                    • Diabetes Prediction
                </li>
            </ul>

            <a href="https://github.com/Gabitzzz">
                <p
                    class="text-xl mt-4"
                    style="font-family: 'Poppins', sans-serif; font-weight:bold;">
                    github.com/Gabitzzz
                </p>
            </a>

        </div>

        <div class="md:w-1/2 " style="margin: initial !important;">
            <a href="https://github.com/Gabitzzz">
                <div class="content-overlay"></div>
                <img :src="git_profile" alt="Gif" class="w-full px-6"/>
            </a>
        </div>

    </div>


    <!--    </div>-->
</template>

<script>


import dws from "/images/DWS.webp";
import ted from "/images/ted.webp";
import patratel from "/images/patratel.webp";
import arhique from "/images/arhique.webp";
import esn from "/images/esn.png";
import git_profile from "/images/github_profile.png";
import {Swiper, SwiperSlide} from 'swiper/vue';
import 'swiper/css';


export default {
    name: "Portfolio",
    data() {
        return {
            ted: ted,
            dws: dws,
            arhique: arhique,
            patratel: patratel,
            esn: esn,
            git_profile: git_profile,
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
