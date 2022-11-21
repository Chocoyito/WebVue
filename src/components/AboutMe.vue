<script>

export default {
    name: "AboutMe",
    data(){
        return{
            nombre_completo: "Roberto Jose Amador Arroliga",
            fecha_de_nacimiento: "09/04/2003"
        }
    }
}

</script>

<template>
    <div class="container">


        <div class="about-me">
            <div class="about-me__info">
                <article class="about-me__yo">
                    <h2>Quien soy</h2>
                    <picture class="about-me__picture">
                        <img class="about-me__img" src="../assets/icons/yo.jpg" alt="yo">
                    </picture>
                </article>

                <article>
                    <h2>Educacion</h2>
                    <p>Once you’ve accepted your flaws, no one can use them against you.</p>
                </article>
                <article>
                    <h2>Carrera</h2>
                    <p>Once you’ve accepted your flaws, no one can use them against you.</p>
                </article>
            </div>
        </div>

        <!--        <div class="about-me__info">
                    <h2 class="no-margin">Quien soy</h2>
                    <p>Adolescens duis proin orci dolore suscipit quis dicant tale. Constituam duo appetere constituam dolore.
                        Elaboraret et dicant velit aliquet. Quem nec laoreet maximus ludus invenire curabitur lectus.</p>-->


    </div>
</template>


<style scoped>
.container {
    padding: 0 2rem;
    width: auto;
    margin: 5rem 0 0 0;
}


@media (min-width: 1080px) {
    .about-me{
        height: 600px;
    }
    .container {
        padding: 0 15rem;
        margin: 10rem 0 0 0;
    }

    .about-me__info{
        display: grid;
        grid-template-columns: repeat(3, 1fr);
    }

    .about-me__yo{
        display: flex;
        flex-direction: column;
        text-align: center;
        width: 300px;
        color: #376DF6;
        border: 2px solid #376DF6;
        border-radius: 32px;
        height: 600px;
    }
}



.about-me__img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
}

/*
.about-me__info {
    text-align: center;
    padding: 0 50px;
}

.about-me__info h2 {
    font-size: 50px;
}
*/


</style>