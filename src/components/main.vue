<script setup>
  const name = "Roberto"
  const carreer = "ingeniero informatico"

</script>

<template>
    <main class="main_container flex">
        <div class="about_me grid">
            <div class="about_me_text flex">
                <h1 class="no-margin">Me llamo <span class="span_name">{{ name }}</span></h1>
                <h2 class="no-margin">Soy un {{carreer}}</h2>
                <p>Maiorum disputationi consequat luptatum potenti. Brute urna magna semper harum solet mei habitasse constituto nisi. Nonumes ancillae imperdiet lacus referrentur salutatus condimentum patrioque aenean pertinacia. Partiendo taciti efficitur reprimique saperet volutpat commodo prompta erroribus.</p>
            </div>
            <!-- Aqui otro div para el boton -->
            <img src="../assets/icons/profile_picture.jpg" alt="">

        </div>
    </main>
</template>

<style scoped>

    @import '../assets/main.css';

    h1{
        font-size: 3.5rem;
    }
    h2{
        font-size: 2.5rem;
    }
    p{
        font-size: 1.5rem;
    }

    img{
        height: auto;
        width: 70%;
        border-radius: 50px;
        filter: drop-shadow(0 0 1.50rem cornflowerblue);
    }

    .span_name{
        color: var(--secundario);
    }
    
    .main_container{
        padding: 10rem 10rem;
        width: auto;
        /* #090909 #111111 */
    }

    .about_me{
        height: 50rem;
        grid-template-columns: 50% 50%;
        justify-items: center;
        align-items: center;
    }

    .about_me_text{
        flex-direction: column;
        text-align: center;
        align-self: start;
        margin-top: 10rem;
    }
    .about_me h2{
        margin-top: 1rem;
        white-space: pre-line;
    }

</style>