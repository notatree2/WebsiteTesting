<script setup>
    import { ref, onMounted} from "vue"
    import { useDark } from "@vueuse/core"
    import projects from "./components/projects.vue"
    const source = ref("https://tech-independence-journey.codeberg.page/")


</script>

<template>
    <div class="h-screen max-w-full bg-gradient-to-b to-slate-600 from-slate-700 from-60%">
        <div class="h-screen text-center mr-48 ml-48">
            <div class=" p-10 text-pretty text-slate-900 space-y-2">
                <h1 class="font-bold text-4xl ">Hello, i am <span class="text-blue-500">notacupofmilk.</span></h1>
                <p class="text-3xl">I am a <span class="text-yellow-500">Christian</span>, a guy who play video games, and i like the internet!</p>


                <br>
                <br>
                <br>

                
            <projects/>
                
                
            </div>

        </div>

    </div>

</template>

<style scoped>

</style>
