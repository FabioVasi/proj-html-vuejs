<script>
export default {
    data() {
        return {
            name: 'AppMain'
        }
    }
}
</script>

<template>

    <main id="main_app">

        <section class="about">
            <div class="container text-center">
                <h1>
                    More About Damon Vaughn
                </h1>
                <h3 style="color: #333333;" class="mt-3 mb-5">
                    Damon Vaughn is a professor of psychology at the University of Toronto, a clinical psychologist and the author of the multi-million copy bestseller "The story of my life".
                </h3>
                <button class="border-0 text-white rounded-3 fw-bold ">
                    Meet The Author
                </button>
            </div>
        </section>
        
    </main>

</template>

<style lang="scss" scoped>
    @use '../assets/scss/partials/variables.scss' as *;

    .about{
        margin: 100px 0;
    }
    h1{
        font-size: 5rem;
        font-family: 'Times New Roman', Times, serif;
        font-style: oblique;
        font-weight: bold;
        color: $yellow;
    }
    button{
        background-color: $green;
        width: 200px;
        height: 40px;
    }
</style>