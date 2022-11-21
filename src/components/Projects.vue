<template>
    <div class="container">
        <div :style="{textAlign:'center'}">
            <h2>Mis proyectos</h2>
            <div class="my-projects">
                <article>
                    <h3>Tal cosa</h3>
                    <picture>

                    </picture>
                </article>
                <article>
                    <h3>Tal cosa</h3>
                    <picture>

                    </picture>
                </article>
                <article>
                    <h3>Tal cosa</h3>
                    <picture>

                    </picture>
                </article>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Projects"
}
</script>

<style scoped>
@media (min-width: 1080px) {
    .container {
        padding: 0 15rem;
        margin: 10rem 0 0 0;
    }
    .my-projects{
        display: grid;
        grid-template-columns: repeat(3, 1fr);
    }
}
</style>