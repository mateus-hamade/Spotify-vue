<template>
    <div class="flex flex-row gap-1 mb-6">
        <div class="w-1 h-1 bg-white rounded-full"></div>
        <div class="w-1 h-1 bg-white rounded-full"></div>
        <div class="w-1 h-1 bg-white rounded-full"></div>
    </div>

    <nav class="flex flex-col gap-1 font-bold">
        <div class="flex flex-col gap-4 font-bold">
            <a href="#" class="flex items-center gap-4">
                <Home color="white"/>
                <p class="text-white">Início</p>
            </a>
            <a href="#" class="flex items-center gap-4 hover:text-white transition-colors">
                <Search color="#9D9D9D"/>
                <p>Buscar</p>
            </a>
            <a href="#" class="flex items-center gap-4 hover:text-white transition-colors">
                <Library color="#9D9D9D"/>
                <p>Sua Biblioteca</p>
            </a>
        </div>
        <div class="mt-10 flex flex-col gap-4">
            <a href="#" class="flex items-center gap-4 hover:text-white transition-colors">
                <div class="w-6 h-6 bg-[#9D9D9D] rounded-sm flex justify-center">
                    <Plus color="black" width="16px"/>
                </div>
                <p>Criar playlist</p>
            </a>
            <a href="#" class="flex items-center gap-4 hover:text-white transition-colors">
                <div class="w-6 h-6 rounded-sm flex justify-center bg-gradient-to-tl from-white to-blue-800 via-indigo-500">
                    <Heart fill="white" color="white" width="14px"/>
                </div>
                <p>Músicas Curtidas</p>
            </a>
        </div>
    </nav> 
</template>

<script lang="ts">
    import { Home, Search, Library, Plus, Heart } from 'lucide-vue-next'

    export default {
        name: 'Nav',
        components: {
            Home,
            Search,
            Library,
            Plus,
            Heart,
        },
    }
</script>