<script setup>

</script>

<template>
    <header class="header">
        <nav class="navbar flex">
            <a href="" class="logo">
                R
            </a>
            <div class="li_items">
                <ul class="no-padding flex">
                    <li><a href="">Inicio</a></li>
                    <li><a href="">Sobre mi</a></li>
                    <li><a href="">Proyectos</a></li>
                </ul>
            </div>
        </nav>
    </header>
</template>


<style scoped>
@import '../assets/main.css';

*{
    color: var(--secundario);
}

.header{
    font-size: 3rem;
    padding: 0 15rem;
}   

.navbar{
    justify-content: space-between;
    align-items: center;
}

.logo{
    padding: 1rem 2rem;
    border: 2px solid var(--secundario);
    border-radius: 16px;
    /*background-color: var(--secundario);*/
    font-weight: bold;
}

ul{
    gap: 4rem;
}

li{
    list-style: none;
}
</style>