<script>
    import Home from './components/home.vue'
    import Skills from './components/skills.vue'
    import About from './components/aboutMe.vue'

    export default{
        name:"Main",

        components: {
            Home, Skills, About
        },
    }
    
</script>

<template>
    <main class="main">
        <Home/>
        <About/>
        <Skills/>
    </main>
</template>



<style scoped>

</style>