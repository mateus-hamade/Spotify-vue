<template>
    <div class="flex justify-center items-center gap-2">
        <img src="../../../public/album-8.jpeg" class="w-14">
        <div class="mr-10">
            <strong class="text-white hover:underline cursor-pointer">Pandora</strong>
            <div class="flex gap-1">
                <p class="text-xs cursor-pointer hover:underline hover:text-white">Sant,</p>
                <p class="text-xs cursor-pointer hover:underline hover:text-white">Thiago Mec,</p>
                <p class="text-xs cursor-pointer hover:underline hover:text-white">Bukola 2Tey</p>
            </div>
        </div>
        <Heart width="20px" color="#1ED760" fill="#1ED760"/>
    </div>
</template>

<script lang="ts">
    import { Heart } from 'lucide-vue-next'

    export default {
        name: 'Music',

        components: {
            Heart,
        },
    }
</script>