<link rel="stylesheet" href="../../../../../Downloads/jquery-flipster-master/src/less/themes/carousel.less">
<template>
    <!--    <div class="w-full px-8 md:px-16 lg:px-24 xl:px-40 pb-24 ">-->

    <p
        class="text-6xl text-center mt-16 "
        style="font-family: 'Poppins', sans-serif; font-weight:bold;">
        About Me
    </p>


    <div class=" mt-12 avatar md:flex items-center justify-between">
        <div class="flex  rounded-full m-8">
            <img :src="me" alt="me" class="grayscale about w-full duration-300 transition ease-in">

        </div>

        <p class="mx-10">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ea enim nemo optio porro quae repellat
            voluptas! Deleniti dicta distinctio eum fugiat incidunt itaque iure, libero nostrum quaerat quam
            sapiente voluptatem.
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ea enim nemo optio porro quae repellat
            voluptas! Deleniti dicta distinctio eum fugiat incidunt itaque iure, libero nostrum quaerat quam
            sapiente voluptatem.

        </p>


    </div>
    <p
        class="text-3xl mt-8 "
        style="font-family: 'Poppins', sans-serif; font-weight:bold;">
        Career
    </p>

    <!--    RESUME  -->
    <div class="flex justify-center px-4 mt-8">
        <div class="timeline">
            <div class="entry">
                <div class="title">
                    <h3>2022</h3>
                    <p>Essex Social Network</p>
                </div>
                <div class="body">
                    <p class="text-xl">
                        Started Essex Social Network, a Social Media Platform for students from University of Essex
                    </p>
                </div>
            </div>
            <div class="entry">
                <div class="title">
                    <h3>2021</h3>
                    <p>Lițcan Nicolae-Gabriel PFA</p>
                </div>
                <div class="body">
                    <p class="text-xl">
                        Founded Lițcan Nicolae-Gabriel PFA and started doing freelance for companies from various
                        fields of activity, including architecture, banking, electricity or e-commerce,</p>
                </div>
            </div>
            <div class="entry">
                <div class="title">
                    <h3>January-March 2021</h3>
                    <p>Title, Company</p>
                </div>
                <div class="body">
                    <p class="text-xl">

                        Handled school's hardware(printers, routers, computers, tablets, CCTV) and used The
                        Integrated Information System of Education in Romania and Edus Platform as software.
                    </p>
                </div>
            </div>
            <div class="entry">
                <div class="title">
                    <h3>2020</h3>
                    <p>Title, Company</p>
                </div>
                <div class="body">
                    <p class="text-xl">Worked on various Projects, including <br>
                        Formula Student, <br>
                        COVID-19 Analysis and Forecasting Program <br>
                        AMY Club <br>
                        House Price Prediction.</p>
                </div>
            </div>

            <div class="entry">
                <div class="title">
                    <h3>2019</h3>
                    <p>Title, Company</p>
                </div>
                <div class="body">
                    <p class="text-xl">Started studying Computer Science at University of Essex and moved out to
                        Colchester, UK.</p>
                </div>
            </div>

        </div>

        <!--            <pdf src="./path/to/static/relativity.pdf"></pdf>-->


    </div>


    <p
        class="text-3xl mt-8 "
        style="font-family: 'Poppins', sans-serif; font-weight:bold;">
        Tech Stalk
    </p>

    <p
        class="text-md mt-4 "
        style="font-family: 'Poppins', sans-serif;">
        Here is my favourite Tech Stack, languages and frameworks that I use every day in most of my projects.
    </p>


    <input type="radio" name="rotateAxis" class="hidden" id="axesY" checked>

    <div class="mx-8">
        <div class="grid max-w-full  grid-cols-2 md:grid-cols-2 lg:grid-cols-3 gap-y-8 content-center">
            <!--LARAVEL -->
            <div
                class="skill px-4 md:flex items-center justify-center mt-8 hover:scale-110 duration-300 transition ease-in">
                <!--                <div class="grid grid-col-2 gap-2  ">-->
                <div class="grid grid-col-1 justify-center    ">

                    <div class="laravel-logo">
                        <img :src="laravel" class="" alt="" width="64" height="64">
                    </div>

                </div>
                <div class="grid grid-col-3 laravel-text ">

                    <p class="  align-top  md:ml-8 text-center">
                        Laravel
                    </p>
                </div>

            </div>

            <!--                    VUE -->
            <div class="skill md:flex items-center justify-center mt-8 hover:scale-110 duration-300 transition ease-in">
                <div class="grid grid-col-1 justify-center    ">
                    <div class="js-logo">
                        <img :src="vue" class="" alt="" width="64" height="64">
                    </div>
                </div>
                <div class="grid grid-col-3 js-text ">

                    <p class="  align-top  md:ml-8 text-center">
                        Vue
                    </p>
                </div>
            </div>

            <!--            TAILWIND-->
            <div class="skill md:flex items-center justify-center mt-8 hover:scale-110 duration-300 transition ease-in">
                <div class="grid grid-col-1 justify-center    ">

                    <div class="css-logo">
                        <img :src="tailwind" class="" alt="" width="64" height="64">
                    </div>

                </div>
                <div class="grid grid-col-3 css-text ">

                    <p class=" align-top md:ml-8 text-center">
                        Tailwind.CSS
                    </p>

                </div>
            </div>

            <!--            HTML    -->
            <div class="skill md:flex items-center justify-center mt-8 hover:scale-110 duration-300 transition ease-in">
                <div class="grid grid-col-1 justify-center    ">
                    <div class="html-logo">
                        <img :src="html" class="" alt="" width="64" height="64">
                    </div>
                </div>

                <div class="grid grid-col-3 html-text ">
                    <p class="mt-2 align-top md:ml-8 text-center">
                        HTML
                    </p>
                </div>
            </div>

            <!--            CSS-->
            <div class="skill md:flex items-center justify-center mt-8 hover:scale-110 duration-300 transition ease-in">
                <div class="grid grid-col-1 justify-center    ">
                    <div class="css-logo">
                        <img :src="css" class="" alt="" width="64" height="64">
                    </div>
                </div>

                <div class="grid grid-col-3 css-text ">
                    <p class="  align-top  md:ml-8 text-center">
                        CSS
                    </p>
                </div>
            </div>

            <!--                        JS      -->
            <div class="skill md:flex items-center justify-center mt-8 hover:scale-110 duration-300 transition ease-in">
                <div class="grid grid-col-1 justify-center    ">
                    <div class="js-logo">
                        <img :src="js" class="" alt="" width="64" height="64">
                    </div>
                </div>

                <div class="grid grid-col-3 js-text ">
                    <p class="align-top md:ml-8 text-center">
                        JavaScript
                    </p>
                </div>
            </div>

            <!--                         SQL      -->
            <div class="skill md:flex items-center justify-center mt-8 hover:scale-110 duration-300 transition ease-in">
                <div class="grid grid-col-1 justify-center    ">

                    <div class="sql-logo">
                        <img :src="sql" class="" alt="" width="64" height="64">
                    </div>

                </div>
                <!--                        <div class="grid grid-col-2 gap-2  ">-->
                <div class="grid grid-col-3 sql-text ">

                    <p class="  align-top  md:ml-8 text-center">

                        SQL
                    </p>
                </div>
            </div>

            <!--            PYTHON      -->
            <div class="skill md:flex items-center justify-center mt-8 hover:scale-110 duration-300 transition ease-in">
                <div class="grid grid-col-1 justify-center    ">
                    <div class="laravel-logo">
                        <img :src="python" class="" alt="" width="64" height="64">
                    </div>
                </div>

                <div class="grid grid-col-3 laravel-text ">
                    <p class="align-top  md:ml-8 text-center">
                        Python
                    </p>
                </div>
            </div>

                    <!--            SKETCH      -->
                    <div class="skill md:flex items-center justify-center mt-8 hover:scale-110 duration-300 transition ease-in">
                        <div class="grid grid-col-1 justify-center    ">

                            <div class="html-logo">
                                <img :src="sketch" class="" alt="" width="64" height="64">
                            </div>

                        </div>
                            <div class="grid grid-col-3 html-text ">
                            <p class="  align-top  md:ml-8 text-center">
                                Sketch
                            </p>
                        </div>
                    </div>


        </div>

    </div>

</template>

<script>
import me from "/images/me.jpg";
import laravel from "/images/laravel.png";
import vue from "/images/vue.png";
import tailwind from "/images/tailwind.png";
import css from "/images/css.png";
import sql from "/images/sql.png";
import python from "/images/python.png";
import sketch from "/images/sketch.png";
import html from "/images/html.svg";
import js from "/images/js.svg";


export default {
    name: "About",
    components: {},
    data() {
        return {
            me: me,
            laravel: laravel,
            vue: vue,
            tailwind: tailwind,
            html: html,
            css: css,
            js: js,
            sql: sql,
            python: python,
            sketch: sketch,
        }
    }
}
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Anton&display=swap");

.hidden {
    position: fixed;
    top: -10000px;
    left: -10000px;
    visibility: hidden;
}


@keyframes rotateOnY {
    5% {
        -webkit-transform: rotateY(90deg);
        transform: rotateY(90deg);
    }
    10% {
        -webkit-transform: rotateY(0deg);
        transform: rotateY(0deg);
    }
}

.laravel-logo {
    width: 64px;
    height: 64px;
}


.js-logo {
    width: 64px;
    height: 64px;
}

.css-logo {
    width: 64px;
    height: 64px;
}

.html-logo {
    width: 64px;
    height: 64px;
}

.sql-logo {
    width: 64px;
    height: 64px;
}


#axesY:checked ~ .mx-8 > .grid > .skill > .grid > .laravel-logo {
    -webkit-animation: rotateOnY 20s infinite linear;
    animation: rotateOnY 20s infinite linear;
    animation-delay: 4s;
}

#axesY:checked ~ .mx-8 > .grid > .skill > .grid > .js-logo {
    -webkit-animation: rotateOnY 20s infinite linear;
    animation: rotateOnY 20s infinite linear;
    animation-delay: 8s;
}

#axesY:checked ~ .mx-8 > .grid > .skill > .grid > .html-logo {
    -webkit-animation: rotateOnY 20s infinite;
    animation: rotateOnY 20s infinite linear;
    animation-delay: 12s;
}

#axesY:checked ~ .mx-8 > .grid > .skill > .grid > .css-logo {
    -webkit-animation: rotateOnY 20s infinite;
    animation: rotateOnY 20s infinite linear;
    animation-delay: 16s;
}

#axesY:checked ~ .mx-8 > .grid > .skill > .grid > .sql-logo {
    -webkit-animation: rotateOnY 20s infinite;
    animation: rotateOnY 20s infinite linear;
    animation-delay: 20s;
}


.laravel-text {
    -webkit-animation: laravel-text 20s infinite;
    animation: laravel-text 20s infinite;
    -webkit-animation-delay: 4s;
    animation-delay: 4s;
}

.js-text {
    -webkit-animation: js-text 20s infinite;
    animation: js-text 20s infinite;
    -webkit-animation-delay: 8s;
    animation-delay: 8s;
}

.html-text {
    -webkit-animation: html-text 20s infinite;
    animation: html-text 20s infinite;
    -webkit-animation-delay: 12s;
    animation-delay: 12s;
}

.css-text {
    -webkit-animation: css-text 20s infinite;
    animation: css-text 20s infinite;
    -webkit-animation-delay: 16s;
    animation-delay: 16s;
}

.sql-text {
    -webkit-animation: css-text 20s infinite;
    animation: css-text 20s infinite;
    -webkit-animation-delay: 20s;
    animation-delay: 20s;
}

@keyframes laravel-text {
    5% {
        transform: scale(1.7);
    }
    15% {
        transform: scale(1.7);
    }
    20% {
        transform: scale(1);
    }
}

@keyframes laravel-text-mobile {
    5% {
        transform: scale(1);
    }
    15% {
        transform: scale(1);
    }
    20% {
        transform: scale(0.8);
    }
}

@keyframes js-text {
    5% {
        transform: scale(1.7);
    }
    15% {
        transform: scale(1.7);
    }
    20% {
        transform: scale(1);
    }
}

@keyframes js-text-mobile {
    5% {
        transform: scale(1);
    }
    15% {
        transform: scale(1);
    }
    20% {
        transform: scale(0.8);
    }
}

@keyframes html-text {
    5% {
        transform: scale(1.7);
    }
    15% {
        transform: scale(1.7);
    }
    20% {
        transform: scale(1);
    }
}

@keyframes html-text-mobile {
    5% {
        transform: scale(1);
    }
    15% {
        transform: scale(1);
    }
    20% {
        transform: scale(0.8);
    }
}

@keyframes css-text {
    5% {
        transform: scale(1.7);
    }
    15% {
        transform: scale(1.7);
    }
    20% {
        transform: scale(1);
    }
}

@keyframes css-text-mobile {
    5% {
        transform: scale(1);
    }
    15% {
        transform: scale(1);
    }
    20% {
        transform: scale(0.8);
    }
}

@keyframes sql-text {
    5% {
        transform: scale(1.7);
    }
    15% {
        transform: scale(1.7);
    }
    20% {
        transform: scale(1);
    }
}

@keyframes sql-text-mobile {
    5% {
        transform: scale(1);
    }
    15% {
        transform: scale(1);
    }
    20% {
        transform: scale(0.8);
    }
}

@media (max-width: 760px) {
    .laravel-text {
        transform: scale(0.8);
        -webkit-animation: laravel-text-mobile 20s infinite;
        animation: laravel-text-mobile 20s infinite;
        -webkit-animation-delay: 4s;
        animation-delay: 4s;
    }

    .js-text {
        transform: scale(0.8);
        -webkit-animation: js-text-mobile 20s infinite;
        animation: js-text-mobile 20s infinite;
        -webkit-animation-delay: 8s;
        animation-delay: 8s;
    }

    .html-text {
        transform: scale(0.8);
        -webkit-animation: html-text-mobile 20s infinite;
        animation: html-text-mobile 20s infinite;
        -webkit-animation-delay: 12s;
        animation-delay: 12s;
    }

    .css-text {
        transform: scale(0.8);
        -webkit-animation: css-text-mobile 20s infinite;
        animation: css-text-mobile 20s infinite;
        -webkit-animation-delay: 16s;
        animation-delay: 16s;
    }

    .sql-text {
        transform: scale(0.8);
        -webkit-animation: sql-text-mobile 20s infinite;
        animation: sql-text-mobile 20s infinite;
        -webkit-animation-delay: 20s;
        animation-delay: 20s;
    }

}


/*html*/


.about {
    -webkit-animation: web-dev 20s infinite;
    animation: about 20s infinite;
    -webkit-animation-delay: 3s;
    /*animation-delay: 6s;*/
}

.about:hover {
    /*-webkit-animation-name: about;*/
    /*-webkit-animation-duration: 2000ms;*/
    /*-webkit-animation-timing-function: ease-in;*/
    filter: grayscale(0);

}

@keyframes about {
    10% {
        transform: scale(1.20);
    }

    20% {
        transform: scale(1.20);
    }
    30% {
        transform: scale(1.20);
    }
    40% {
        transform: scale(1);
    }
}


</style>

