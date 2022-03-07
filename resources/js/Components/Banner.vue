<template>
    <div class="w-full px-4  sm:px-8 md:px-16 lg:px-24 xl:px-40 pt-24 md:pt-40">


        <div class="flex-none sm:flex align-center items-center">



            <div class="flex-auto">



                <p
                    class="text-3xl mb-2 flex justify-between"
                    style="font-family: 'Poppins', sans-serif; font-weight:bold;">

                    Hello,
                    <span class="wave">👋🏽  </span>

                </p>

                <div id="text" class="text-6xl lg:text-8xl">
                    <!-- content generated with JS -->
                </div>

                <h1
                    class="text-4xl"
                    style="font-family: 'Poppins', sans-serif; font-weight:bold;">
                    Full Stack Web Developer
                    <br>
                    & Student

                </h1>

                <div class="flex mt-6">
                    <button class="btn btn-outline rounded-full">CONTACT ME</button>
                    <img :src="github" class="w-12 ml-2 border rounded-full border-current hover:bg-current" alt="">
                    <img :src="github" class="w-12 ml-2 border rounded-full border-current hover:bg-current" alt="">
                    <img :src="github" class="w-12 ml-2 border rounded-full border-current hover:bg-current" alt="">
                </div>



                <div class="mockup-code zoom-in-out-box pt-8 scale-110 transition duration-300 shadow-xl mx-6 mt-8 transition ease-in">
                    <pre data-prefix="$"><code>npm run watch</code></pre>
                    <pre data-prefix=">" class="text-warning"><code>building...</code></pre>
                    <pre data-prefix=">" class="text-success"><code>Done!</code></pre>
                </div>

<!--                <div class="floating"-->
<!--                     style="height: 50px; width: 50px; background: rgb(200,200,200);">-->
<!--                </div>-->


            </div>


            <div class="flex-auto">
                <img :src="gif" alt="Gif" width="550"/>
            </div>

        </div>




    </div>

</template>



<script>
import gif from "/images/Programming.gif";
import github from "/images/github.png";


export default {
    name: "Banner",
    data(){
        return{
            gif: gif,
            github: github,
        }
    },

}
</script>


<style scoped>
.wave {
    animation-name: wave-animation; /* Refers to the name of your @keyframes element below */
    animation-duration: 2.5s; /* Change to speed up or slow down */
    animation-iteration-count: infinite; /* Never stop waving :) */
    transform-origin: 70% 70%; /* Pivot around the bottom-left palm */
    display: inline-block;
}


@keyframes wave-animation {
    0% {
        transform: rotate(0.0deg)
    }
    10% {
        transform: rotate(14.0deg)
    }
    /* The following five values can be played with to make the waving more or less extreme */
    20% {
        transform: rotate(-8.0deg)
    }
    30% {
        transform: rotate(14.0deg)
    }
    40% {
        transform: rotate(-4.0deg)
    }
    50% {
        transform: rotate(10.0deg)
    }
    60% {
        transform: rotate(0.0deg)
    }
    /* Reset for the last half to pause */
    100% {
        transform: rotate(0.0deg)
    }
}

.floating {
    animation-name: floating;
    animation-duration: 3s;
    animation-iteration-count: infinite;
    animation-timing-function: ease-in-out;
    margin-left: 30px;
    margin-top: 5px;
}



.box {
    animation-name: scale;
    animation-duration: 3s;
    animation-iteration-count: infinite;
    animation-timing-function: ease-in-out;
    margin-left: 30px;
    margin-top: 5px;
}


.zoom-in-out-box {
    animation: zoom-in-zoom-out 2.5s ease infinite;
}

@keyframes zoom-in-zoom-out {
    0% {
        transform: scale(1, 1);
    }
    50% {
        transform: scale(1.1, 1.1);
    }
    100% {
        transform: scale(1, 1);
    }
}





</style>
