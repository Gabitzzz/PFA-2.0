<template>
<!--        <p-->
<!--            class="text-4xl  sm:text-6xl mb-2 flex justify-center mt-16 "-->
<!--            style="font-family: 'Poppins', sans-serif; font-weight:bold;">-->

<!--            Contact me-->
<!--        </p>-->


        <!-- component -->
        <div class="grid grid-cols-1 md:grid-cols-2 items-center mt-16">
            <div class="mx-2 px-2 md:px-8">
                <p class="w-full max-w-lg mt-4 mb-16 text-4xl font-bold">
                    Let's Get in Touch
                </p>

                <p class="w-full max-w-lg mt-4 text-lg ">
                    Either you have an inquiry about a potential project, a question about programming or whatever pops
                    into your mind, drop me a message and I will get back to you as soon as possible.
                </p>


                <p class="w-full max-w-lg mt-8 text-lg ">
                    <a href="https://goo.gl/maps/MDxLQff43DTB3WJ98">
                        ADDRESS: Brănești, Ilfov, România
                    </a> <br>
                    <a href="mailto:litcangabi@gmail.com">
                        EMAIL: litcangabi@gmail.com
                    </a> <br>
                    <a href="tel:+40773800815">
                        PHONE: +40 773 800 815
                    </a> <br>
                </p>
            </div>

            <form class="w-full max-w-lg mt-8 bg-contact p-8 rounded-2xl">

                <div class="flex flex-wrap -mx-3 mb-6">

                   <div class="w-full px-3">
                       <label class="block uppercase tracking-wide  text-xs font-bold mb-2"
                              for="grid-first-name">
                           Name
                       </label>
                       <input
                           class="bg-gray-800 appearance-none block w-full text-gray-700 border border-gray-800 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
                           id="grid-first-name" type="text" >
                   </div>
                </div>

                <div class="flex flex-wrap -mx-3 mb-6">
                    <div class="w-full px-3">
                        <label class="block uppercase tracking-wide text-xs font-bold mb-2">
                            Email
                        </label>
                        <input
                            class="bg-gray-800 appearance-none block w-full text-gray-700 border border-gray-800 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
                            id="email" type="email">
                    </div>
                </div>
                <div class="flex flex-wrap -mx-3 mb-6">
                    <div class="w-full px-3">
                        <label class="block uppercase tracking-wide text-xs font-bold mb-2">
                            Message
                        </label>
                        <textarea
                            class=" no-resize appearance-none block w-full bg-gray-800 text-gray-700 border border-gray-800 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500 h-48 resize-none"
                            id="message"></textarea>
                    </div>
                </div>
                <div class="md:flex md:items-center">
                        <a
                            class="btn btn-outline rounded-full px-16"
                            type="button">
                            Send
                        </a>
                    <div class="md:w-2/3"></div>
                </div>
            </form>


        </div>

</template>

<script>
export default {
    name: "Contact"
}
</script>

<style scoped>
.bg-contact{
    background-color: #191D24;
}
</style>
