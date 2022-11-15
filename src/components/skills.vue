<script setup>

</script>

<template>
    <div class="container">
        <section class="my_skills_section">
            <h2 class="no-margin">Que tal</h2>
            <div class="my_skills_div grid">
                <article class="my_skills_article flex">
                    <h3 class="no-margin">Diseno web</h3>
                    <p>
                        Nobody exists on purpose. Nobody belongs anywhere. Everybody is going to die.
                    </p>
                </article>

                <article class="my_skills_article flex">
                    <h3 class="no-margin">Diseno web</h3>
                    <p>
                        Nobody exists on purpose. Nobody belongs anywhere. Everybody is going to die.
                    </p>
                </article>

                <article class="my_skills_article flex">
                    <h3 class="no-margin">Diseno web</h3>
                    <p>
                        Nobody exists on purpose. Nobody belongs anywhere. Everybody is going to die.
                    </p>
                </article>
            </div>
        </section>
    </div>
</template>

<style scoped>
    *{
        color: white;
    }
    h2{
        font-size: 3.6rem;
    }
    h3{
        font-size: 2.8rem;
    }
    p{
        font-size: 2.2rem;
    }
    .container{
        width: auto;
        background: linear-gradient(180deg, #37AEF6 , #376DF6); /*45deg tambien se veia bonito xd*/
        padding: 0 5rem;

        /*
           Celestito header #
           Azulito header #376DF6
        */
    }

    .my_skills_section{
        padding: 5rem 0;
    }

    .my_skills_section h2{
        text-align: center;
    }
    .my_skills_div{
        grid-template-columns: 1fr 1fr 1fr;
        grid-template-rows: auto;
        margin-top: 5rem;
    }
    .my_skills_article{
        flex-direction: column;
        align-items: center;
        text-align: center;
    }


</style>