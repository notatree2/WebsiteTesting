<script setup>
    import { ref, onMounted} from "vue"
    import { useDark } from "@vueuse/core"
    const source = ref("https://tech-independence-journey.codeberg.page/")
    const youtube = ref("https://www.youtube.com/@notacupofmilk2021")


</script>

<template>


                <h1 class="font-semibold text-3xl">Projects</h1>
                <!-- project grid -->
                 <br>
                 <div class="grid grid-cols-2 gap-3 grid-rows-2">
                    
                    <!-- button -->
                     <a class="" :href="source">
                        <button  class="space-y-2 p-5  font-bold rounded-lg shadow-lg bg-slate-700 transition-all hover:bg-slate-600 focus:ring-2 focus:ring-blue-950 overflow-hidden ">Tech Independence Journey 
                            <div class=" font-semibold mr-24 ml-24" >
                                <p>Unfinished project to take back your privacy from big tech by suggesting privacy-respecting alternatives.</p>
                            </div>
                        </button>
                     </a>
                     <a class="" :href="youtube">
                        <button  class="space-y-2 p-5  font-bold rounded-lg shadow-lg bg-slate-700 transition-all hover:bg-slate-600 focus:ring-2 focus:ring-blue-950 overflow-hidden">YouTube
                            
                            <div class=" font-semibold mr-24 ml-24" >
                                <p>You can check out my youtube channel, but i dont post on my YouTube channel very often. </p>
                            </div>
                        </button>
                     </a>
                        
                        
                     
                    
                    
                </div>

</template>

<style scoped>

</style>
