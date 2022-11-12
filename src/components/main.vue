<template>
    <main>





        <div class="main_container">


            <div class="grid about_me">
                
                <div class="me_container">
                    <img class="me_img" src="../assets/icons/picture.jpg" alt="">
                    <h2 class="h2_me no-margin">Me llamo <span class="span_name">Roberto</span></h2>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Molestias, nihil deserunt. Mollitia facilis temporibus voluptas.</p>
                    <p>
                        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Enim dolorum ex harum, necessitatibus omnis totam.
                    </p>
                </div>

                

                <div class="yo">
                    

                    <h1>No tengo idea, me doy pena</h1>
                </div>
                
            </div>
        </div>
    </main>
</template>

<style scoped>
    @import '../assets/main.css';
    .span_name{
        color: var(--secundario);
    }
    
    .main_container{
        margin: 10rem 10rem;
        /* padding: 0 autorem; */
        /*  
            #090909
            #111111
         */
    }
    .me_container{
        border-radius: 16px;
        background-color: #111111;
        padding: 0 2rem;
    }

    .h2_me{
        font-size: 2rem;
    }
    .me_container p{
        font-size: 1.6rem;
    }

    p{
        font-size: 1.4rem;
    }

    .about_me{
        grid-template-columns: 35% 65%;
        text-align: center;
        align-items: center;
        /* justify-items: center; */
        column-gap: 4rem;
    }

    .me_img{
        background-size: cover;
        width: 150px;
        height: 150px;
        border-radius: 50%;  
        margin: 2rem 0;
    }

</style>