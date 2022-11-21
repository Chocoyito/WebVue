<script setup>
    
</script>

<template>
    <nav class="navbar">
        <a href="" class="navbar__logo">
            R
        </a>
        <div>
            <ul class="main-nav__list no-padding">
                <li class="main-nav__item"><a href="">Inicio</a></li>
                <li class="main-nav__item"><a href="">Sobre mi</a></li>
                <li class="main-nav__item"><a href="">Proyectos</a></li>
            </ul>
        </div>
    </nav>
</template>

<style scoped>

.navbar{
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.main-nav__item{
    list-style: none;
}

.navbar__logo{
    padding: 1rem 2rem;
    border: 2px solid var(--secundario);
    border-radius: 16px;
    font-weight: bold;
}


.main-nav__list{
    gap: 4rem;
    display: flex
}
</style>