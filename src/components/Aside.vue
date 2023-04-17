<template>
    <aside class="w-60 bg-black p-6 text-[#9D9D9D]">
        <Nav />
        <Playlist />
    </aside>
</template>
  
<script lang="ts">
    import Nav from './aside/Nav.vue'
    import Playlist from './aside/Playlist.vue'

    export default {
        name: 'Aside',
        components: {
        Nav,
        Playlist,
        }
    }
</script>