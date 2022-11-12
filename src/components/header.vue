<template>
    <header class="header">
        <nav class="navbar flex">
            <ul class="no-padding flex">
                <li>Inicio</li>
                <li>Sobre mi</li>
                <li>Proyectos</li>
            </ul>
            <div class="button">
                Boton
            </div>
        </nav>
    </header>
</template>


<style scoped>
@import '../assets/main.css';

.header{
    border-radius: 16px;
    font-size: 2rem;
}

.navbar{
    justify-content: space-between;
    align-items: center;
}

ul{
    gap: 4rem;
}

li{
    list-style: none;
}
</style>