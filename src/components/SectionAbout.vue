<script>
export default {
    name: 'SectionAbout',
    data() {
        return {

        }
    }
}
</script>

<template>
    
    <section class="about">

        <div class="container text-center">
            <h1 class="font">
                More About Damon Vaughn
            </h1>
            <h3 class="mt-3 mb-5 grey-d">
                Damon Vaughn is a professor of psychology at the University of Toronto, a clinical psychologist and the author of the multi-million copy bestseller "The story of my life".
            </h3>
            <button class="meet border-0 text-white rounded-3 fw-bold">
                Meet The Author
            </button>
        </div>

    </section>

</template>

<style lang="scss" scoped>
    @use '../assets/scss/partials/variables.scss' as *;

    .yellow{
        color: $yellow;
    }
    .green{
        color: $green;
    }
    .bg-section{
        background-color: $bfg_section;
    }
    .grey-d{
        color: $dark_grey;
    }
    .grey-l{
        color: $light_grey;
    }
    .blue{
        color: $blue;
    }
    .font{
        font-family: 'Times New Roman', Times, serif;
    }



    .about{
        margin: 100px 0;
    }
    h1{
        font-size: 5rem;
        font-style: oblique;
        font-weight: bold;
        color: $yellow;
    }
    .meet{
        background-color: $green;
        width: 200px;
        height: 40px;
    }
</style>