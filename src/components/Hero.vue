 <script>
    export default {
        name: "Hero",
        data() {
            return {
                name: "Roberto",
                carreer: "ingeniero informatico"
            }
        }
    }
</script>

<template>
    <div class="container">
        <div class="hero grid">
            <div class="hero__info">
                <h1>Me llamo <span class="hero__name">{{ name }}</span></h1>
                <h2>Soy un {{carreer}}</h2>
                <div class="hero__button">
                    <button class="hero__button--btn">Mas sobre mi</button>
                </div>
            </div>
            <picture class="hero__image">
                <img class="me" src="../assets/icons/yotuani.png" alt="">
            </picture>
        </div>
    </div>
</template>

<style scoped>

    h1{
        font-size: 6rem;
        margin: 0;
    }
    h2{
        font-size: 3rem;
        margin: 0;
    }
    .hero__info h1{
        white-space: nowrap;
    }
    .hero__name{
        color: var(--secundario);
    }
    .hero__info h2{
        margin-top: 1rem;
        white-space: pre-line;
    }
    p{
        font-size: 2.2rem;
    }



    
    .container{
        padding: 0 10rem;
        width: auto;
        margin: 10rem 0 0 0;
        /* #090909 #111111 */
    }


    .hero{
        display: flex;
        height: auto;
        width: 100%;
        /*grid-template-columns: 50% 50%;
        grid-template-rows: auto;*/
        justify-content: space-around;
        align-content: center;
    }

    .hero__info{
        display: flex;
        flex-direction: column;
        text-align: center;
        align-self: center;
    }


    .hero__button{
        margin-top: 5rem;
    }
    .hero__button--btn{
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
    .hero__button--btn:hover{
        background: var(--secundario);
        color: var(--primario);
        transform: scale(1.1) perspective(1px)
    }

    .hero__image{
        width: auto;
        text-align: center;
        justify-content: center;
        align-items: center;
    }
    .me{
        height: 512px;
        width: auto;
        padding-bottom: 10rem;
    }

</style>
