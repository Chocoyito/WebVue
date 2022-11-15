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
                <div class="div_btn">
                    <button class="btn">Mas sobre mi</button>
                </div>
            </div>
            <div class="box flex">
                <img class="me" src="../assets/icons/yo2.png" alt="">
            </div>
        </div>
    </main>
</template>

<style scoped>

    @import '../assets/main.css';

    h1{
        font-size: 6rem;
    }
    h2{
        font-size: 3rem;
    }
    p{
        font-size: 2.2rem;
    }


    .span_name{
        color: var(--secundario);
    }
    
    .main_container{
        padding: 0;
        width: auto;
        /* #090909 #111111 */
    }


    .about_me{
        height: auto;
        width: 100%;
        grid-template-columns: 50% 50%;
        grid-template-rows: auto;
        justify-items: center;
        align-items: center;
        margin: 15rem 0;
        padding: 0 15rem;


        border-radius: 30px;

    }

    .about_me_text{
        flex-direction: column;
        text-align: center;
        align-self: center;
    }

    .about_me h1{
        white-space: nowrap;
    }
    .about_me h2{
        margin-top: 1rem;
        white-space: pre-line;
    }

    .div_btn{
        margin-top: 5rem;
    }
    .btn{
        padding: 8px 8rem;
        background: var(--secundario) none;
        font-size: 2rem;
        border: none;
        border-radius: 8px;
        outline: none;
        cursor: pointer;
        color: var(--primario);
    }

    .box{
        justify-content: center;
        align-items: center;
    }
    .me{
        height: auto;
        width: 70%
    }

</style>