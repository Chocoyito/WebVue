<script setup>
  const name = "Roberto"
  const carreer = "ingeniero informatico"

</script>

<template>
    <div class="container flex">
        <div class="home grid">
            <div class="home_text flex">
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
        <!--<svg style="transform:rotate(0deg); transition: 0.3s" viewBox="0 0 1440 150" version="1.1" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0"><stop stop-color="rgba(55, 174, 246, 1)" offset="0%"></stop><stop stop-color="rgba(55, 109, 246, 1)" offset="100%"></stop></linearGradient></defs><path style="transform:translate(0, 0px); opacity:1" fill="url(#sw-gradient-0)" d="M0,15L60,30C120,45,240,75,360,75C480,75,600,45,720,30C840,15,960,15,1080,12.5C1200,10,1320,5,1440,12.5C1560,20,1680,40,1800,45C1920,50,2040,40,2160,47.5C2280,55,2400,80,2520,87.5C2640,95,2760,85,2880,82.5C3000,80,3120,85,3240,85C3360,85,3480,80,3600,77.5C3720,75,3840,75,3960,62.5C4080,50,4200,25,4320,17.5C4440,10,4560,20,4680,30C4800,40,4920,50,5040,50C5160,50,5280,40,5400,42.5C5520,45,5640,60,5760,65C5880,70,6000,65,6120,72.5C6240,80,6360,100,6480,105C6600,110,6720,100,6840,85C6960,70,7080,50,7200,35C7320,20,7440,10,7560,27.5C7680,45,7800,90,7920,112.5C8040,135,8160,135,8280,117.5C8400,100,8520,65,8580,47.5L8640,30L8640,150L8580,150C8520,150,8400,150,8280,150C8160,150,8040,150,7920,150C7800,150,7680,150,7560,150C7440,150,7320,150,7200,150C7080,150,6960,150,6840,150C6720,150,6600,150,6480,150C6360,150,6240,150,6120,150C6000,150,5880,150,5760,150C5640,150,5520,150,5400,150C5280,150,5160,150,5040,150C4920,150,4800,150,4680,150C4560,150,4440,150,4320,150C4200,150,4080,150,3960,150C3840,150,3720,150,3600,150C3480,150,3360,150,3240,150C3120,150,3000,150,2880,150C2760,150,2640,150,2520,150C2400,150,2280,150,2160,150C2040,150,1920,150,1800,150C1680,150,1560,150,1440,150C1320,150,1200,150,1080,150C960,150,840,150,720,150C600,150,480,150,360,150C240,150,120,150,60,150L0,150Z"></path></svg>-->
    </div>
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
    
    .container{
        padding: 0;
        width: auto;
        margin: 10rem 0 0 0;
        flex-flow: wrap;
        /* #090909 #111111 */
    }


    .home{
        height: auto;
        width: 100%;
        grid-template-columns: 50% 50%;
        grid-template-rows: auto;
        justify-items: center;
        align-items: center;
        padding: 0 15rem;


        border-radius: 30px;

    }

    .home_text{
        flex-direction: column;
        text-align: center;
        align-self: center;
    }

    .home h1{
        white-space: nowrap;
    }
    .home h2{
        margin-top: 1rem;
        white-space: pre-line;
    }

    .div_btn{
        margin-top: 5rem;
    }
    .btn{
        padding: 8px 8rem;
        /*background: var(--secundario) none;*/
        background: transparent;
        font-size: 2rem;
        border: 2px solid var(--secundario);
        border-radius: 16px;
        outline: none;
        cursor: pointer;
        color: var(--secundario);
        transition: all .3s ease;
    }
    .btn:hover{
        background: var(--secundario);
        color: var(--primario);
        transform: scale(1.1) perspective(1px)
    }

    .box{
        justify-content: center;
        align-items: center;
    }
    .me{
        height: auto;
        width: 70%;
        padding-bottom: 10rem;
    }

</style>