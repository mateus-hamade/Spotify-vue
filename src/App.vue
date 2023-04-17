<template>
    <div class="h-screen flex flex-col text-sm">
      <div class="flex flex-1 h-2/3">
        <Aside />
        <Main />
      </div>
      <Footer />
    </div>
</template>

<script setup>
import {SkipBack, SkipForward, Pause, Repeat, Shuffle, Mic2, ListMusic, Volume2, Laptop2} from 'lucide-vue-next';

import Aside from './components/Aside.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';

</script>