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
                <img class="me" src="../assets/icons/yotuani.png" alt="">
            </div>
        </div>
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
