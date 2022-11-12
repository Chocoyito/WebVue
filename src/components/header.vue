<template>
    <header class="header">
        <nav class="navbar flex">
            <a class="logo">
                R
            </a>
            <div class="li_items">
                <ul class="no-padding flex">
                    <li>Inicio</li>
                    <li>Sobre mi</li>
                    <li>Proyectos</li>
                </ul>
            </div>
            
            <div class="button">
                Boton
            </div>
        </nav>
        
    </header>
</template>


<style scoped>
@import '../assets/main.css';

.header{
    font-size: 2.5rem;
    padding: 0 15rem;
}   

.navbar{
    justify-content: space-between;
    align-items: center;
}

.logo{
    padding: 1rem 2rem;
    border-radius: 16px;
    background-color: var(--secundario);
    font-weight: bold;
}

ul{
    gap: 4rem;
}

li{
    list-style: none;
}
</style>