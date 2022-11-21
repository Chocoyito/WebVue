<script>

export default {
    name: "AboutMe"
}

</script>

<template>
    <div class="container">


        <div class="about-me">
            <h1 class="no-margin">
                Mas sobre mi
            </h1>
            <h2 class="no-margin">
                Proximamente 💀
            </h2>
        </div>

<!--        <picture class="about-me__picture">
            <img class="about-me__img" src="../assets/icons/yo.jpg">
        </picture>

        <div class="about-me__info">
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
    color: #376DF6;
}
.about-me {
    display: flex;
    text-align: center;
    font-size: 25px;
    flex-direction: column;
}
@media (min-width: 1080px) {
    .container{
        padding: 0 15rem;
        margin: 10rem 0 0 0;
    }
}



/*.about-me__picture {
    width: 350px;
    height: 350px;
    display: flex;
    justify-content: center;
}

.about-me__img {
    border-radius: 50%;
}

.about-me__info {
    text-align: center;
    padding: 0 50px;
}

.about-me__info h2 {
    font-size: 50px;
}*/


</style>