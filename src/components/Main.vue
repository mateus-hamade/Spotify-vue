<template>
    <main class="flex-1 bg-main p-6 text-white overflow-auto scrollbar scrollbar-thumb-white/20">
        <Nav />
        <PlayList />
        <Daily />        
  </main>
</template>

<script>
    import Nav from './main/Nav.vue'
    import PlayList from './main/PlayList.vue'
    import Daily from './main/Daily.vue'

    export default {
        name: 'main',

        components: {
            Nav,
            PlayList,
            Daily
        }
    };
</script>