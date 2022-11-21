<script setup>
    
</script>

<template>
    <nav class="navbar">
        <div class="navbar__logo">
            <a href="" class="navbar__icon">
                R
            </a>
        </div>
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

.navbar__icon{
    padding: 1rem 2rem;
    font-weight: bold;
    border: 2px solid var(--secundario);
    border-radius: 16px;
}

.main-nav__item{
    list-style: none;
}

.main-nav__list{
    gap: 40px;
    display: flex;
    justify-content: center;
}

.navbar__logo{
    margin-top: 30px;
}

.navbar{
    display: flex;
    flex-direction: column;
    text-align: center;
}

@media (min-width: 1080px) {
    .navbar__logo{
        margin-top: 0;
    }

    .navbar{
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        margin: 0 50px;
    }

    .navbar__icon{
        padding: 1rem 2rem;
        border: 2px solid var(--secundario);
        border-radius: 16px;
        font-weight: bold;
    }

    .main-nav__list{
        gap: 40px;
        display: flex;
    }
}








</style>