<script>
import SectionAbout from './SectionAbout.vue';

export default {
    name: 'AppMain',
    data() {
        return {
            
        }
    },
    components: {
        SectionAbout
    }
}
</script>

<template>

    <main id="main_app">

        <SectionAbout/>

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

        <section class="critics">

            <div class="container">
                <div class="row">
                    <div class="col-8 pe-5">
                        <div class="card border-0">
                            <h2 class="font mb-4 fw-bold fs-1">What The Critics Say</h2>
                            <h6 style="color: #49a987;" class="mb-4">TESTIMONIALS FROM AROUND THE WORLD</h6>
                        </div>
                        <div class="testimonial text-white text-start">
                            <div class="shadow">
                                <h2 class="font fs-1 fw-bold border-bottom m-0 border-dark-subtle pb-5">Best Author Of His Generation</h2>
                                <h5 class="fw-medium mt-5 mb-0">
                                    This book will change your perspective on life
                                </h5>
                                <span class="d-block mt-4 mb-3">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur, sequi! Itaque quam id exercitationem architecto ducimus officia mollitia ad cumque illo! Impedit nihil commodi dolorem consectetur voluptatem mollitia fugit veniam!
                                </span>
                                <span class="d-block">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae, amet ipsa tenetur adipisci debitis eum error voluptatibus aspernatur suscipit commodi non nisi ducimus dolores, accusantium ratione tempora in labore sint.
                                </span>
                                <p style="font-style: inherit;" class="mt-5">
                                    <!--La lettera E usa un font gothico che non sono riuscito a trovare-->
                                    <span style="font-family: 'Times New Roman', Times, serif; font-size: 24px;">E</span> Justine Kilpatrick, <a style="color: #49a987; text-decoration: none;" href="#">The New York Times</a>
                                </p>
                            </div>
                        </div>
                    </div>

                    <div class="col-4 ps-5 text-center">
                        <div class="card border-0">
                            <button class="read mt-4 align-self-end border-0 text-white rounded-3 fw-bold">
                                Read All Testimonials
                            </button>
                        </div>
                        <div class="message p-4 card rounded-0 mt-5 border-0">
                            <h3 class="font mb-3 fw-bold fs-4 pt-3">A True Masterpierce, Bravo!</h3>
                            <p class="mb-4">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint exercitationem illo quibusdam laboriosam recusandae, quaerat excepturi nesciunt quasi consectetur asperiores consequatur at unde repellendus cumque ea? Magni laborum quos molestias.
                            </p>
                        </div>
                        <div class="d-flex justify-content-start align-items-center mt-3">
                            <img class="pe-4" src="../assets/img/theguardian-xsmall.png" alt="">
                            <p class="m-0 fw-medium">Gerald Hendley, The Guardian</p>                            
                        </div>

                        <div class="message p-4 card rounded-0 mt-5 border-0">
                            <h3 class="font mb-3 fw-bold fs-4 pt-3">A Unique View On The World</h3>
                            <p class="mb-4">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint exercitationem illo quibusdam laboriosam recusandae, quaerat excepturi nesciunt quasi consectetur asperiores consequatur at unde repellendus cumque ea? Magni laborum quos molestias.
                            </p>
                        </div>
                        <div class="d-flex justify-content-start align-items-center mt-3">
                            <img class="pe-4" src="../assets/img/globe-xsmall.png" alt="">
                            <p class="m-0 fw-medium">Mary Maxey, The Globe And Mail</p>                            
                        </div>
                        
                    </div>
                </div>
            </div>

        </section>

        <section class="upcoming">

            <div class="container text-center">
                <h2 class="font fs-1 fw-bold m-0">Upcoming Events</h2>
                <h5 style="color: #f4b429;" class="fw-medium pt-3 pb-5 m-0">MEET THE AUTHOR IN PERSON</h5>

                <div class="row">

                    <div class="col-4 pe-4">
                        <div class="card border-0 rounded-0">
                            <img src="../assets/img/event-05-400x240.jpg" class="card-img-top rounded-0" alt="">
                            <div class="card-body p-4">
                                <h4 class="card-title border-bottom pb-4">Chicago Book Signing</h4>
                                <p class="card-text">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat sint dignissimos sunt quibusdam sed nihil at eum eos, quos, unde id vitae natus obcaecati fugit molestias enim magni laudantium totam.
                                </p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="col-4 pe-4 ps-4">
                        <div class="card border-0 rounded-0">
                            <img src="../assets/img/event-04-400x240.jpg" class="card-img-top rounded-0" alt="">
                            <div class="card-body p-4">
                                <h4 class="card-title border-bottom pb-4">Chicago Book Signing</h4>
                                <p class="card-text">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat sint dignissimos sunt quibusdam sed nihil at eum eos, quos, unde id vitae natus obcaecati fugit molestias enim magni laudantium totam.
                                </p>
                            </div>
                        </div>
                    </div>

                    <div class="col-4 ps-4">
                        <div class="card border-0 rounded-0">
                            <img src="../assets/img/event-07-400x240.jpg" class="card-img-top rounded-0" alt="">
                            <div class="card-body p-4">
                                <h4 class="card-title border-bottom pb-4">Chicago Book Signing</h4>
                                <p class="card-text">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat sint dignissimos sunt quibusdam sed nihil at eum eos, quos, unde id vitae natus obcaecati fugit molestias enim magni laudantium totam.
                                </p>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
            
        </section>

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
                                <h6 class="read-time mt-3 mb-5">BE NOTIFIED ABOUT BOOK SIGNING TOUR DATES</h6>
                                <form class="row g-3">
                                    <div class="col-8 ps-5">
                                        <input style="height: 50px;" type="text" class="form-control" placeholder="Insert your email ...*">
                                    </div>
                                    <div class="col-4">
                                        <button style="height: 50px;" type="submit" class="btn text-white fw-medium meet">Subscribe</button>
                                    </div>
                                </form>
                                <p style="color: #c6c4c4;" class="mt-5">
                                    Donec fringilla nunc eu turpis dignissim, at euismod sapien tincidunt. Maecenas eleifend congue cursus.
                                </p>
                            </div>   
                        </div>
                        <div class="col-3"></div>
                    </div>
                </div>
            </div>

        </section>

        <section class="dig">
            
            <div class="container text-center">
                <h2 class="font fs-1 fw-bold m-0">Dig A Little Deeper Into Damon Vaughn</h2>
                <h5 style="color: #49a987;" class="fw-medium pt-3 pb-5 m-0">FIND OUT MORE ABOUT AUTHOR HIMSELF</h5>
                <div class="row">
                    <div class="col-4 pe-4">
                        <div class="me card border-0">
                            <div class="darkin">
                                <h3 class="text-white pb-3 m-0">About Me</h3>
                                <div class="border-bottom border-dark-subtle mb-4 w-25"></div>
                                <p class="pb-4 m-0 fw-medium read-time">Vestibulum ante ipsum primis</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-4 pe-4 ps-4">
                        <div class="latest card border-0">
                            <div class="darkin">
                                <h3 class="text-white pb-3 m-0">My Latest Book</h3>
                                <div class="border-bottom border-dark-subtle mb-4 w-25"></div>
                                <p class="pb-4 m-0 fw-medium read-time">Vestibulum ante ipsum primis</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-4 ps-4">
                        <div class="signing card border-0">
                            <div class="darkin">
                                <h3 class="text-white pb-3 m-0">Book Signing</h3>
                                <div class="border-bottom border-dark-subtle mb-4 w-25"></div>
                                <p class="pb-4 m-0 fw-medium read-time">Vestibulum ante ipsum primis</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </section>

        <section class="articles">

            <div class="container">
                <div class="row">
                    
                    <div class="col-8">
                        <div class="card bg-transparent border-0">
                            <h2 class="font fs-1 fw-bold m-0">Recent Articles</h2>
                            <h5 style="color: #49a987;" class="fw-medium pt-3 pb-4 m-0">READ THE LATEST ENTRIES</h5>
                        </div>
                        <div class="card p-5 border-0 rounded-0">
                            <img src="../assets/img/20-Tips-800x471.jpg" class="card-img-top rounded-0" alt="">
                            <div class="card-body">
                                <h3 class="card-title pb-2 m-0">20 Creativity tips</h3>
                                <p class="card-text mb-4">
                                    By admin | October 24th, 2019 | Categiories:Event, Tips & Tricks
                                </p>
                                <h6 class="m-0">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta, repudiandae laboriosam? Obcaecati blanditiis ab earum numquam aliquid iste ut illum!
                                </h6>
                            </div>
                        </div>
                    </div>

                    <div class="col-4">
                        <div class="card bg-transparent border-0 pb-5">
                            <button class="read mt-4 align-self-end border-0 text-white rounded-3 fw-bold">
                                All Articles
                            </button>
                        </div>
                        <div class="card p-5 border-0 rounded-0">
                            <img src="../assets/img/thumb-13-2x-320x202.jpg" class="card-img-top rounded-0" alt="">
                            <div class="card border-0">
                                <h4 class="card-title pt-3 pb-2 m-0">What's On Your Booklist?</h4>
                                <p class="card-text pb-4">
                                    October 24th, 2019 | 0 Comments
                                </p>
                            </div>
                            <img src="../assets/img/thumb-08-2x-320x202.jpg" class="card-img-top rounded-0" alt="">
                            <div class="card border-0">
                                <h4 class="card-title pt-3 pb-2 m-0">Istanbul Travel Guide</h4>
                                <p class="card-text pb-4">
                                    October 24th, 2019 | 0 Comments
                                </p>
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


    .about, .critics, .dig{
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


    

    .audible, .upcoming, .articles{
        background-color: $bfg_section;
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
    .read-time{
        color: $yellow;
    }



    .testimonial{
        background-image: url(../assets/img/testimonial2-2x.jpg);
        background-size: cover;
        height: 800px;
        border-radius: 0 0 10rem 0;
    }
    .shadow{
        background-color: rgba(0, 0, 0, 0.360);
        background-size: cover;
        height: 800px;
        border-radius: 0 0 10rem 0;
        display: flex;
        flex-direction: column;
        justify-content: center;
        padding: 100px;
    }
    .read{
        background-color: $yellow;
        width: 240px;
        height: 40px;
    }
    .message{
        background-color: $bfg_section;
    }



    .upcoming, .articles{
        padding: 80px 0;
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



    .me{
        background-image: url(../assets/img/box-1.jpg);
        background-size: cover;
        border-radius: 0 0 4rem 0;
        height: 500px;
    }
    .latest{
        background-image: url(../assets/img/box-4.jpg);
        background-size: cover;
        border-radius: 0 0 4rem 0;
        height: 500px;
    }
    .signing{
        background-image: url(../assets/img/box-3.jpg);
        background-size: cover;
        border-radius: 0 0 4rem 0;
        height: 500px;
    }
    .darkin{
        background-color: rgba(0, 0, 0, 0.120);
        background-size: cover;
        border-radius: 0 0 4rem 0;
        height: 500px;
        display: flex;
        flex-direction: column;
        justify-content: end;
        align-items: center;
    }
</style>