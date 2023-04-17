<template>
    <div class="mt-10">
        <h1 class="font-bold text-3xl">Boa tarde</h1>
        
        <div class="grid grid-cols-3 grid-rows-2 gap-4 mt-4 rounded">
            <a href="#" class="bg-white/10 group rounded flex overflow-auto items-center gap-4 text-base hover:bg-white/20 transition-colors">
                <img src="/album-1.jpeg" class="w-[80px] h-[80px]"/>
                <strong>Jorge e Mateus</strong>

                <button class="p-2 rounded-full bg-green-600 ml-auto mr-8 invisible group-hover:visible group-hover:shadow-xl">
                    <Play fill="black" color="black" viewBox="-2 0 24 24"/>
                </button>
            </a>
            
            <a href="#" class="bg-white/10 group rounded flex overflow-auto items-center gap-4 text-base hover:bg-white/20 transition-colors">
                <img src="/album-8.jpeg" class="w-[80px] h-[80px]"/>
                <strong>Pandora</strong>

                <button class="p-2 rounded-full bg-green-600 ml-auto mr-8 invisible group-hover:visible group-hover:shadow-xl">
                    <Play fill="black" color="black" viewBox="-2 0 24 24"/>
                </button>
            </a>
            
            <a href="#" class="bg-white/10 group rounded flex overflow-auto items-center gap-4 text-base hover:bg-white/20 transition-colors">
                <img src="/album-2.jpeg" class="w-[80px] h-[80px]"/>
                <strong>Mateus e Kauan</strong>

                <button class="p-2 rounded-full bg-green-600 ml-auto mr-8 invisible group-hover:visible group-hover:shadow-xl">
                    <Play fill="black" color="black" viewBox="-2 0 24 24"/>
                </button>
            </a>
            
            <a href="#" class="bg-white/10 group rounded flex overflow-auto items-center gap-4 text-base hover:bg-white/20 transition-colors">
                <img src="/album-3.jpeg" class="w-[80px] h-[80px]"/>
                <strong>MPB</strong>

                <button class="p-2 rounded-full bg-green-600 ml-auto mr-8 invisible group-hover:visible group-hover:shadow-xl">
                    <Play fill="black" color="black" viewBox="-2 0 24 24"/>
                </button>
            </a>

            <a href="#" class="bg-white/10 group rounded flex overflow-auto items-center gap-4 text-base hover:bg-white/20 transition-colors">
                <img src="/album-4.jpeg" class="w-[80px] h-[80px]"/>
                <strong>Funk Hits</strong>

                <button class="p-2 rounded-full bg-green-600 ml-auto mr-8 invisible group-hover:visible group-hover:shadow-xl">
                    <Play fill="black" color="black" viewBox="-2 0 24 24"/>
                </button>
            </a>
            
            <a href="#" class="bg-white/10 group rounded flex overflow-auto items-center gap-4 text-base hover:bg-white/20 transition-colors">
                <img src="/album-5.jpeg" class="w-[80px] h-[80px]"/>
                <strong>Eletrônica Hits</strong>

                <button class="p-2 rounded-full bg-green-600 ml-auto mr-8 invisible group-hover:visible group-hover:shadow-xl">
                    <Play fill="black" color="black" viewBox="-2 0 24 24"/>
                </button>
            </a>
        </div>
    </div>
</template>

<script lang="ts">
    import { Play } from 'lucide-vue-next'

    export default {
        name: 'PlayList',

        components: {
            Play,
        },
    }
</script>