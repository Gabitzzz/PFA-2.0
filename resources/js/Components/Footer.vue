<template>
    <footer class="footer p-10 bg-base-200 text-base-content">
        <div>
            <img :src="logo"
                 class="w-16 md:w-32 "
                 style=" filter:  brightness(0) invert(1);"
                 alt="logo">
            <p>ACME Industries Ltd.<br>Providing reliable tech since 1992</p>
        </div>
        <div>
            <span class="footer-title">Services</span>
            <a class="link link-hover">Branding</a>
            <a class="link link-hover">Design</a>
            <a class="link link-hover">Marketing</a>
            <a class="link link-hover">Advertisement</a>
        </div>
        <div>
            <span class="footer-title">Company</span>
            <a class="link link-hover">About us</a>
            <a class="link link-hover">Contact</a>
            <a class="link link-hover">Jobs</a>
            <a class="link link-hover">Press kit</a>
        </div>

    </footer>
</template>

<script>
import logo from "/images/logo.png";

export default {
    name: "Footer",
    data(){
        return{
            logo:logo,
        }
    }
}
</script>

<style scoped>

</style>
