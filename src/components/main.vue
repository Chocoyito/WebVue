<template>
    <main>
        <div class="grid main_container">
            <h1 class="no-margin">Me llamo <span class="span_name">Roberto Jose Amador</span></h1>
            <h1>Hola</h1>
        </div>
    </main>
</template>

<style scoped>
    @import '../assets/main.css';

    .span_name{
        color: var(--secundario);
    }
    
    .main_container{
        margin: 10rem 0;
        padding: 15rem 15rem;
        grid-template-columns: repeat(2, 1fr);
        align-items: center;
        text-align: center;
        border-radius: 16px;
        background-color: #111111;

        /*  
            #090909
            #111111
         */
    }

</style>