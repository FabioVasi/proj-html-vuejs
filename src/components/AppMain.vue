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
                                <h6 class="read-time mt-2">NO TIME TO READ? NO PROBLEM. LISTEN TO IT</h6>
                                <p style="color: #c6c4c4;" class="mt-3">
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
    .audible{
        background-color: $bfg_section;
    }
    .banner-one{
        background-image: url(../assets/img/banner.jpg);
        background-size: cover;
        height: 600px;
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
    .read-time{
        color: $yellow;
    }
</style>