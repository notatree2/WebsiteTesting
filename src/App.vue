<script setup>
    import { ref, onMounted} from "vue"
    import { useDark } from "@vueuse/core"
    import projects from "./components/projects.vue"
    const source = ref("https://tech-independence-journey.codeberg.page/")

    const status = ref("")

    const randomization = Math.floor(Math.random() * 8)
    if (randomization === 0) {
        status.value = "Romans 8:31"

    } else if (randomization === 1) {
        status.value = "My favorite food? I don't know, but my favorite color is blue."
    } else if (randomization === 2) {
        status.value = "My favorite game as of 9/8/24 is BTD6."
    } else if (randomization === 3) {
        status.value  = "I am notacupofmilk"
    } else if (randomization === 4) {
        status.value = "https://www.youtube.com/watch?v=ytWz0qVvBZ0 (its not a rickroll)"
    } else if (randomization === 5) {
        status.value = "I live on Earth."
    } else if (randomization === 6) {
        status.value = "I apologize if these messages are dull, i can barely think of anything"
    } else if (randomization === 7) {
        status.value = "🤯🤯🤯"
    } else {
        status.value = "I play ROBLOX, my username is Ifartedchicken."
    }
 
    const ChangeStatus = () => {
    const randomization2 = Math.floor(Math.random() * 8)
    if (randomization2 === 0) {
        status.value = "Romans 8:31"
    } else if (randomization2 === 1) {
        status.value = "My favorite food? I don't know, but my favorite color is blue."
    } else if (randomization2 === 2) {
        status.value = "My favorite game as of 9/8/24 is BTD6."
    } else if (randomization2 === 3) {
        status.value  = "I am notacupofmilk"
    } else if (randomization2 === 4) {
        status.value = "https://www.youtube.com/watch?v=ytWz0qVvBZ0 (its not a rickroll)"
    } else if (randomization2 === 5) {
        status.value = "I live on Earth."
    } else if (randomization2 === 6) {
        status.value = "I apologize if these messages are dull, i can barely think of anything"
    } else if (randomization2 === 7) {
        status.value = "🤯🤯🤯"
    } else {
        status.value = "I play ROBLOX, my username is Ifartedchicken."
    }
    }

</script>

<template>
    <div class="h-screen max-w-full bg-gradient-to-b to-slate-600 from-slate-700 from-70%">
        <div class="h-screen text-center mr-48 ml-48">
            <div class=" p-10 text-pretty text-slate-900 space-y-2">
                <h1 class="font-bold text-4xl ">Hello, i am <span class="text-blue-500">notacupofmilk.</span></h1>
                <p class="text-3xl">I am a <span class="text-yellow-500">Christian</span>, a guy who play video games, and i like the internet!</p>
                

                <br>
                <br>
                <p @click="ChangeStatus" class="text-xl font-bold text-slate-400 animate-pulse">{{ status }}</p>
                <br>
                <br>

                
            <projects/>
                
                
            </div>

        </div>

    </div>

</template>

<style scoped>

</style>
