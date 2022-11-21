 <script>

 export default {
     name: "AboutMe"
 }

</script>

<template>
    <div class="container">
        <div class="about-me">
            <picture class="about-me__picture">
                <img class="about-me__img" src="../assets/icons/profile_picture.jpg" alt="">
            </picture>

            <div class="about-me__info">
                <h2 class="no-margin">Quien soy</h2>
                <p>Adolescens duis proin orci dolore suscipit quis dicant tale. Constituam duo appetere constituam dolore. Elaboraret et dicant velit aliquet. Quem nec laoreet maximus ludus invenire curabitur lectus.</p>
            </div>
        </div>

    </div>
</template>


<style scoped>
    .container{
        padding: 0 10rem;
        width: auto;
        margin: 10rem 0 0 0;
    }
    .about-me{
        display: grid;
        grid-template-columns: 1fr 1fr;
        align-items: center;
        justify-items: center;
    }
    .about-me__picture  {
        width: 512px;
        height: 512px;
        display: flex;
        justify-content: center;
    }
    .about-me__img{
        border-radius: 50px;
    }
    .about-me__info h2{
        font-size: 50px;
    }


</style>