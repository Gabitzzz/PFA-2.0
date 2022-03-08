<template>
        <p
            class="text-6xl mb-2 flex justify-center mt-16 "
            style="font-family: 'Poppins', sans-serif; font-weight:bold;">

            Contact me
        </p>


        <!-- component -->
        <div class="grid grid-cols-1 md:grid-cols-2 items-center">
            <div class="mx-4 px-8">
                <p class="w-full max-w-lg mt-8 text-4xl font-bold">
                    Let's Get in Touch
                </p>

                <p class="w-full max-w-lg mt-8 text-lg ">
                    Either you have an inquiry about a potential project, a question about programming or whatever pops
                    into your mind, drop me a message and I will get back to you as soon as possible.
                </p>
                <p class="w-full max-w-lg mt-8 text-lg ">

                    ADDRESS: Brănești, Ilfov, România
                    EMAIL: litcangabi@gmail.com
                    PHONE: +40 773 800 815
                </p>
            </div>

            <form class="w-full max-w-lg mt-8 bg-contact p-8 rounded-2xl">

                <div class="flex flex-wrap -mx-3 mb-6">

                   <div class="w-full px-3">
                       <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2"
                              for="grid-first-name">
                           Name
                       </label>
                       <input
                           class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
                           id="grid-first-name" type="text" >
                   </div>
                </div>

                <div class="flex flex-wrap -mx-3 mb-6">
                    <div class="w-full px-3">
                        <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">
                            E-mail
                        </label>
                        <input
                            class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
                            id="email" type="email">
                    </div>
                </div>
                <div class="flex flex-wrap -mx-3 mb-6">
                    <div class="w-full px-3">
                        <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2">
                            Message
                        </label>
                        <textarea
                            class=" no-resize appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500 h-48 resize-none"
                            id="message"></textarea>
                    </div>
                </div>
                <div class="md:flex md:items-center">
                    <div class="md:w-1/3">
                        <button
                            class="shadow bg-teal-400 hover:bg-teal-400 focus:shadow-outline focus:outline-none text-white font-bold py-2 px-4 rounded"
                            type="button">
                            Send
                        </button>
                    </div>
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
