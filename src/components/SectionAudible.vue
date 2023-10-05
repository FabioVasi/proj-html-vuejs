<script>
export default {
    name: 'SectionAudible',
    data() {
        return {

        }
    }
}
</script>

<template>

    <section class="audible pt-5">

        <div class="container mb-5">
            <div class="row">

                <div class="col-3">
                    <div>
                        <a href="#">
                            <img src="../assets/img/ebay-logotan-2x-200x66.png" alt="">
                        </a>
                    </div>
                </div>
                <div class="col-3">
                    <div>
                        <a href="#">
                            <img src="../assets/img/audible-logotan-2x-200x66.png" alt="">
                        </a>
                    </div>
                </div>
                <div class="col-3">
                    <div>
                        <a href="#">
                            <img src="../assets/img/bb-logotan-2x-200x66.png" alt="">
                        </a>
                    </div>
                </div>
                <div class="col-3">
                    <div>
                        <a href="#">
                            <img src="../assets/img/kindlefire-logotan-2x-200x66.png" alt="">
                        </a>
                    </div>
                </div>
                
            </div>
        </div>

        <div class="banner-one">

            <div class="container text-center">
                <div class="row">

                    <div class="col-6">
                        <div class="">
                            <img class="smartphone" height="500px" src="../assets/img/audible-app-2x-400x418.png" alt="">
                        </div>                         
                    </div>
                    <div class="col-6">

                        <div class="new-kindle ps-5 pe-5">
                            <h2 class="audio-book text-white fs-1">
                                New Audiobook
                            </h2>
                            <h6 class="yellow mt-2">NO TIME TO READ? NO PROBLEM. LISTEN TO IT</h6>
                            <p class="mt-3 grey-l">
                                Donec fringilla nunc eu turpis dignissim, at euismod sapien tincidunt. Maecenas eleifend congue cursus.
                            </p>
                            <div class="d-flex justify-content-center align-items-center">

                                <div class="col-4 text-white">
                                    <a href="#">
                                        <img src="../assets/img/audible-logo.png" alt="">
                                    </a>    
                                </div>
                                <div class="col-4">
                                    <a href="#">
                                        <img src="../assets/img/bn-logo-tall.png" alt="">
                                    </a>                                
                                </div>
                                <div class="col-4">
                                    <a href="#">
                                        <img src="../assets/img/kindle-logo-tall.png" alt="">
                                    </a>
                                </div>

                            </div>
                        </div>
                        
                    </div>

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



    .banner-one{
        background-image: url(../assets/img/banner.jpg);
        background-size: cover;
    }
    .smartphone{
        margin-top: 100px;
    }
    .new-kindle{
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    .audio-book{
        font-family: 'Times New Roman', Times, serif;
    }
    .audible{
        background-color: $bfg_section;
    }
</style>