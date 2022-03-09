<template>


    <div class="navbar bg-base-100 mb-40 shadow-xl rounded-box fixed mb-32" style="z-index: 20000">
        <!--        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">-->
<!--        <div class="w-full px-4  sm:px-8 md:px-16 lg:px-24 xl:px-40">-->
            <div class="w-full px-4   sm:px-8 md:px-16 lg:px-24 xl:px-40">


            <div class="flex-1">

                <img :src="logo"
                     class="w-16 md:w-24 "
                     style=" filter:  brightness(0) invert(1);"
                     alt="logo">
            </div>

            <div class="navbar-center hidden lg:flex">
                <ul class=" menu-horizontal "
                    style="font-family: 'Poppins', sans-serif; font-weight: normal;">
                    <li><a class="px-8 rounded-full underline-opening">HOME</a></li>
                    <li><a class="px-8 rounded-full underline-opening">PORTFOLIO</a></li>
                    <li><a class="px-8 rounded-full underline-opening">ABOUT ME</a></li>
                    <li><a class="px-8 rounded-full underline-opening">CONTACT</a></li>
                </ul>
            </div>
            <div class="flex-none">
                <div class="dropdown dropdown-end ">
                    <label tabindex="0" class="btn btn-ghost btn-circle lg:hidden">
                        <div class="indicator">
                            <svg xmlns="http://www.w3.org/2000/svg"
                                 class="h-5 w-5 hamburger"
                                 fill="none"
                                 viewBox="0 0 24 24"
                                 stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                      d="M4 6h16M4 12h16M4 18h7"/>
                            </svg>

                        </div>
                    </label>

                    <div tabindex="0" class="mt-3 card card-compact dropdown-content w-52 bg-base-100 shadow">
                        <div class="card-body ">

                            <ul class="menu menu-vertical lg:menu-horizontal bg-base-100 rounded-box">
                                <li><a class="hover:bg-gray-50 hover:text-gray-900">HsOME</a></li>
                                <li><a class="hover:bg-gray-50 hover:text-gray-900">PORTFOLIO</a></li>
                                <li><a class="hover:bg-gray-50 hover:text-gray-900">ABOUT ME</a></li>
                                <li><a class="hover:bg-gray-50 hover:text-gray-900">CONTAsCT</a></li>
                            </ul>

                        </div>
                    </div>


                </div>



            </div>


        </div>


    </div>
</template>

<script>
import logo from "/images/logo2.png";


export default {
    name: "Navbar",
    data() {
        return {
            logo: logo,
        }
    }
}
</script>

<style scoped>

.indicator {
    animation: crescendo 2s alternate infinite ease-in;
}

@keyframes crescendo {
    0% {
        transform: scale(1);
    }
    100% {
        transform: scale(1.8);
    }
}

body, html {
    margin: 0;
    font: bold 14px/1.4 'Open Sans', arial, sans-serif;
    background: #000;
}

ul {
    padding: 0;
    list-style: none;
    text-align: center;
}

.menu-horizontal li {
    display: table-cell;
    position: relative;
}

.menu-horizontal a {
    color: #fff;
    text-transform: uppercase;
    text-decoration: none;
    letter-spacing: 0.15em;

    display: inline-block;
    position: relative;
}

.menu-horizontal a:after {
    background: none repeat scroll 0 0 transparent;
    bottom: -10px;
    content: "";
    display: block;

    height: 2px;
    left: 50%;
    position: absolute;
    background: #fff;
    transition: width 0.3s ease 0s, left 0.3s ease 0s;
    width: 0;
}

.menu-horizontal a:hover:after {
    width: 100%;
    left: 0;
}

@media screen and (max-height: 300px) {
    ul {
        margin-top: 40px;
    }
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

/*#axesY:checked ~ .grid > .skill > .grid > .logo {*/
/*    -webkit-animation: rotateOnY 20s infinite linear;*/
/*    animation: rotateOnY 20s infinite linear;*/
/*    animation-delay: 4s;*/
/*}*/

</style>
