<template>
    <div class="flex items-center gap-4">
        <Mic2 width="18px" class="cursor-pointer"/>
        <ListMusic width="18px" class="cursor-pointer"/>
        <Laptop2 width="18px" class="cursor-pointer"/>
        <Volume2 width="18px" class="cursor-pointer"/>
        <div class="w-24 h-1 rounded-full bg-[#9D9D9D]">
            <div class="w-12 h-1 rounded-full bg-white"></div>
        </div>
        <maximize-2 width="18px" class="cursor-pointer"/>
    </div>
</template>

<script>
    import {Mic2, ListMusic, Laptop2, Volume2, Maximize2} from 'lucide-vue-next';

    export default {
        name: 'Config',

        components: {
            Mic2,
            ListMusic,
            Laptop2,
            Volume2,
            Maximize2,
        }
    }
</script>