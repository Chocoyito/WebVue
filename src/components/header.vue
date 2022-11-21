<script>
    import Navbar from './Navbar.vue'

    export default{
        name: "Header",
        components: {
            Navbar
        },
        data(){
            return{
                textColor: '#376DF6'
            }
        }
    }
</script>

<template>
    <header class="header">
        <Navbar :style="{color: textColor}"/>
    </header>
</template>


<style scoped>
@import '../assets/main.css';

.header{
    font-size: 3rem;
    padding: 0 2rem;
}
@media (min-width: 1080px) {
    .header{
        padding: 0 15rem;
    }
}


</style>