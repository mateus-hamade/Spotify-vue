<template>
    <div class="flex flex-col items-center gap-3">
        <div class="flex justify-center items-center gap-6">
            <Shuffle width="18px" class="cursor-pointer"/>
            <SkipBack fill="#9D9D9D" width="18px" class="cursor-pointer"/>
            <div class="bg-white p-1.5 rounded-full transition hover:scale-105 cursor-pointer">
                <Pause color="black" fill="black" width="18px" height="18px"/>
            </div>
            <SkipForward fill="#9D9D9D" width="18px" class="cursor-pointer"/>
            <Repeat width="18px" class="cursor-pointer"/>
        </div> 
        <div class="flex items-center gap-3">
            <span class="text-xs">1:28</span>
            <div class="w-96 h-1 rounded-full bg-[#9D9D9D]">
                <div class="w-40 h-1 rounded-full bg-white"></div>
            </div>
            <span class="text-xs">4:46</span>
        </div>
    </div>
</template>

<script lang="ts">
    import { SkipBack, SkipForward, Pause, Repeat, Shuffle } from 'lucide-vue-next'

    export default {
        name: 'Player',

        components: {
            SkipBack,
            SkipForward,
            Pause,
            Repeat,
            Shuffle,
        },
    }
</script>