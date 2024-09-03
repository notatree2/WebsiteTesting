<script setup>
    import { ref, onMounted} from "vue"
    import { useDark } from "@vueuse/core"
    const source = ref("https://tech-independence-journey.codeberg.page/")


</script>

<template>


                <h1 class="font-semibold text-3xl">Projects</h1>
                <!-- project grid -->
                 <br>
                 <div class="grid grid-cols-2 group gap-3 ">
                    
                    <!-- button -->
                    
                    <button class="group-active:bg-slate-500 p-5 font-semibold  rounded-lg shadow-lg bg-slate-700 transition-all group-hover:bg-slate-600 " :href="source">Tech Independence Journey</button>
                
                </div>

</template>

<style scoped>

</style>
