<template>
    <!--    <div class="w-full px-4 sm:-mt-32 md:mt-0  sm:px-8 md:-pt-32  xl:px-40 py-8">-->

    <input type="checkbox" id="my-modal" class="modal-toggle">
    <div class="modal">
        <div class="modal-box">
            <div class="flex justify-center">
               <div>
                   <figure class="px-6 pt-6">
                       <img
                           class="mask mask-hexagon"
                           :src="design" alt="design" width="140">
                   </figure>
                   <h3 class="flex justify-center font-bold text-lg mt-2">Product Design</h3>
               </div>
            </div>
            <p class="py-4">I work with certain design tools to create high-fidelity designs and
                prototypes. I design accessible and usable products which aid business growth.</p>
            <div class="modal-action">
                <label for="my-modal" class="btn">CLOSE</label>
            </div>
        </div>
    </div>


    <div class="flex-none grid justify-items-center md:flex justify-center lg:mx-16">
        <div class="md:hover:scale-110 duration-300 transition ease-in">
            <div
                class="card product-design bg-base-200  duration-300 shadow-xl mx-6 py-4 mt-8">
                <figure class="px-6 pt-6">
                    <img
                        class="mask mask-hexagon"
                        :src="design" alt="design" width="140">
                </figure>
                <div class=" items-center text-center m-4">
                    <h2 class="font-bold text-lg ">Product Design</h2>
                    <p class="text-sm mt-2">I work with certain design tools to create high-fidelity designs and
                        prototypes. I design accessible and usable products which aid business growth.</p>
                    <label for="my-modal" class="btn modal-button mt-4">SEE MORE</label>
                </div>
            </div>
        </div>

        <div class="md:hover:scale-110 duration-300 transition ease-in">
            <div
                class="card web-dev bg-base-200  duration-300 shadow-xl mx-6 py-4 mt-8">
                <figure class="px-6 pt-6">
                    <img
                        class="mask mask-circle"
                        :src="webdev" alt="webdev" width="140">
                </figure>
                <div class=" items-center text-center m-4">
                    <h2 class="font-bold text-lg ">Web Development</h2>
                    <p class="text-sm mt-2">I use various web technologies to develop attractive websites which
                        converts
                        visitors to customers. I develop creative and responsive website layouts.</p>
                    <label for="my-modal2" class="btn modal-button mt-4">SEE MORE</label>
                </div>
            </div>
        </div>

        <input type="checkbox" id="my-modal2" class="modal-toggle">
        <div class="modal">

            <div class="modal-box flex-none grid justify-items">
               <div class="flex justify-center">
                   <div>
                       <figure class="px-6 pt-6">
                           <img
                               class="mask mask-circle"
                               :src="webdev" alt="webdev" width="140">
                       </figure>
                       <h3 class="font-bold text-lg mt-2 flex justify-center">Web Development</h3>
                   </div>
               </div>
                <p class="py-4">I use various web technologies to develop attractive websites which
                    converts
                    visitors to customers. I develop creative and responsive website layouts.</p>
                <div class="modal-action">
                    <label for="my-modal2" class="btn">CLOSE</label>
                </div>
            </div>
        </div>

        <div class="md:hover:scale-110 duration-300 transition ease-in">
            <div
                class="card digital-marketing bg-base-200  duration-300 shadow-xl py-4 mx-6 mt-8">
                <figure class="px-6 pt-6">
                    <img
                        class="mask mask-squircle"
                        :src="mrk" alt="webdev" width="140">
                </figure>
                <div class=" items-center text-center m-4">
                    <h2 class="font-bold text-lg ">Digital Marketing</h2>
                    <p class="text-sm mt-2">I identify and evaluates new digital technologies and use web analytics
                        tools to measure site traffic to better optimize marketing campaigns.</p>
                    <label for="my-modal3" class="btn modal-button mt-4">SEE MORE</label>
                </div>

            </div>


        </div>
        <input type="checkbox" id="my-modal3" class="modal-toggle">
        <div class="modal">
            <div class="modal-box">
               <div class="flex justify-center">
                   <div>
                       <figure class="px-6 pt-6">
                           <img
                               class="mask mask-squircle"
                               :src="mrk" alt="webdev" width="140">
                       </figure>
                       <h3 class="font-bold text-lg flex justify-center mt-2">Digital Marketing</h3>
                   </div>
               </div>
                <p class="py-4">I identify and evaluates new digital technologies and use web analytics
                    tools to measure site traffic to better optimize marketing campaigns.</p>
                <div class="modal-action">
                    <label for="my-modal3" class="btn">CLOSE</label>
                </div>
            </div>
        </div>

    </div>
</template>

<script>
import design from "/images/design.png";
import webdev from "/images/webdev.png";
import mrk from "/images/mrk.png";


export default {
    name: "Services",
    data() {
        return {
            design: design,
            webdev: webdev,
            mrk: mrk,
        }
    }
}
</script>

<style scoped>

.product-design {
    -webkit-animation: product-design 20s infinite;
    animation: product-design 20s infinite;
    -webkit-animation-delay: 3s;
    animation-delay: 3s;
}

.product-design:hover {
    background-color: #191D24;
}

@keyframes product-design {
    10% {
        transform: scale(1.15);
        background-color: #191D24;

    }
    20% {
        transform: scale(1);
        background-color: #242933;
    }
}

.web-dev {
    -webkit-animation: web-dev 20s infinite;
    animation: web-dev 20s infinite;
    -webkit-animation-delay: 6s;
    animation-delay: 6s;
}

/*.web-dev:hover {*/
/*    background-color: #191D24;*/
/*    -webkit-animation-name: web-dev-reverse;*/
/*    -webkit-animation-duration: 2000ms;*/
/*    -webkit-animation-timing-function: ease-in;*/
/*}*/

@keyframes web-dev {
    10% {
        transform: scale(1.15);
        background-color: #191D24;
    }
    20% {
        transform: scale(1);
        background-color: #242933;


    }
}


@keyframes web-dev-reverse {
    10% {
        transform: scale(1);
        background-color: #191D24;
    }
    20% {
        transform: scale(1);
        background-color: #242933;


    }
}


.digital-marketing {
    -webkit-animation: digital-marketing 20s infinite;
    animation: digital-marketing 20s infinite;
    -webkit-animation-delay: 3s;
    animation-delay: 3s;
}

.digital-marketing:hover {
    background-color: #191D24;


}

@keyframes digital-marketing {
    10% {
        transform: scale(1.15);
        background-color: #191D24;
    }
    20% {
        transform: scale(1);
        background-color: #242933;

    }
}


</style>
