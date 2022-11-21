<script>
    import Hero from './Hero.vue'
    import AboutMe from './AboutMe.vue'

    export default{
        name:"Main",

        components: {
            Hero,
            AboutMe
        },
    }

</script>

<template>
    <main class="main">
        <Hero/>
        <AboutMe/>
    </main>
</template>



<style scoped>

</style>