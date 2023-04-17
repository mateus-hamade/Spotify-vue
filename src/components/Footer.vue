<template>
    <footer class="flex justify-between items-center bg-footer text-[#9D9D9D] p-4">
        <Music />
        <Player />
        <Config />
      </footer>
</template>

<script>
    import Player from './footer/Player.vue';
    import Music from './footer/Music.vue';
    import Config from './footer/Config.vue';

    export default {
        name: 'Footer',

        components: {
            Player,
            Music,
            Config,
        }
    }
</script>