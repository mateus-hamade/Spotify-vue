<template>
    <div class="flex justify-between items-center">
        <div class="flex gap-5">
            <button class="bg-black/40 rounded-full p-1">
                <ChevronLeft color="#fff" size="24" />
            </button>
            <button class="bg-black/20 rounded-full p-1">
                <ChevronRight color="#fff" size="24" />
            </button>
        </div>
        <div class="flex items-center justify-between bg-black/20 rounded-full w-36 p-2">
            <div class="rounded-full bg-black/30 w-8 h-8 flex justify-center p-1"><User width="20px"/></div>
            <p class="font-bold">Mateus</p>
            <ChevronDown />
        </div>
    </div>
</template>

<script lang="ts">
    import { ChevronLeft, ChevronRight, ChevronDown, User } from 'lucide-vue-next'

    export default {
        name: 'Nav',

        components: {
            ChevronLeft,
            ChevronRight,
            ChevronDown,
            User
        },
    }
</script>