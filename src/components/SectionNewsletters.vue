<script>
export default {
    name: 'SectionNewsletters',
    data() {
        return {
            
        }
    }
}
</script>

<template>

    <section class="newsletters">
            
        <div class="banner-two">    
            <div class="container h-100 text-center">
                <div class="row h-100">
                    <div class="col-3"></div>
                    <div class="col-6">
                        <div class="subscribe">
                            <h2 class="audio-book text-white fs-1 mb-3">
                                Subscribe To My Newsletter
                            </h2>
                            <h6 class="yellow mt-3 mb-5">BE NOTIFIED ABOUT BOOK SIGNING TOUR DATES</h6>
                            <form class="row g-3">
                                <div class="col-8 ps-5">
                                    <input type="text" class="form-control" placeholder="Insert your email ...*">
                                </div>
                                <div class="col-4">
                                    <button type="submit" class="btn text-white fw-medium meet">Subscribe</button>
                                </div>
                            </form>
                            <p class="mt-5 grey-l">
                                Donec fringilla nunc eu turpis dignissim, at euismod sapien tincidunt. Maecenas eleifend congue cursus.
                            </p>
                        </div>   
                    </div>
                    <div class="col-3"></div>
                </div>
            </div>
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



    .banner-two{
        background-image: url(../assets/img/banner-2.jpg);
        background-size: cover;
        height: 600px;
    }
    .subscribe{
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    .meet{
        background-color: $green;
        width: 200px;
        height: 50px;
    }
    input{
        height: 50px;
    }
</style>