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

                <div class="div_btn">
                    <button class="btn">Mas sobre mi</button>
                </div>
            </div>
            <!-- Aqui otro div para el boton -->
            <div class="box">
                <div class="circle">
                    <img class="me" src="../assets/icons/yo2.png" alt="">
                </div>
                <img class="me" src="../assets/icons/yo2.png" alt="">
            </div>

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

    .me{
        height: auto;
        width: 100%;
    }

    .span_name{
        color: var(--secundario);
    }
    
    .main_container{
        padding: 0 0;
        width: auto;
        /* #090909 #111111 */
    }

    .box{
        position: relative;
        text-align: center;
        width: 300px;
        height: 450px;
        background: #fff;
        margin: 20px 40px;
    }
    .box::before{
        content: '';
        position: absolute;
        bottom: 0;
        left: 0;
        width: 300px;
        height: 300px;
        background: transparent;
        border-radius: 50%;
        z-index: 1;
        box-shadow: 0 100px 0 40px #fff;
        overflow: hidden;
    }
    .box .circle{
        position: absolute;
        bottom: 0;
        left: 0;
        width: 300px;
        height: 300px;
        background: var(--secundario);
        overflow: hidden;
        border-radius: 50%;
    }
    .box .circle img,
    .box img{
        position: absolute;
        bottom: 0;
        left: 50%;
        transform: translateX(-50%);
        height: 450px;
    }

    .about_me{
        height: 50rem;
        grid-template-columns: 50% 50%;
        justify-items: center;
        align-items: center;
        padding: 0 10rem;
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

    .div_btn{
        margin-top: 1rem;
    }
    .btn{
        padding: 8px 8rem;
        background: var(--secundario) none;
        border: none;
        border-radius: 16px;
        outline: none;
        cursor: pointer;
        color: var(--primario);
    }
</style>