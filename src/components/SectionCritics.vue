<script>
export default {
    name: 'SectionCritics',
    data() {
        return {
            
        }
    }
}
</script>

<template>

    <section class="critics">

        <div class="container">
            <div class="row">
                <div class="col-8 pe-5">

                    <div class="card border-0">
                        <h2 class="font mb-4 fw-bold fs-1">What The Critics Say</h2>
                        <h6 class="mb-4 green">TESTIMONIALS FROM AROUND THE WORLD</h6>
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
                            <p class="mt-5">
                                <!--La lettera E usa un font gothico che non sono riuscito a trovare-->
                                <span class="font fs-4">E</span> Justine Kilpatrick, <a class="text-decoration-none green" href="#">The New York Times</a>
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
                    <div class="bg-section p-4 card rounded-0 mt-5 border-0">
                        <h3 class="font mb-3 fw-bold fs-4 pt-3">A True Masterpierce, Bravo!</h3>
                        <p class="mb-4">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint exercitationem illo quibusdam laboriosam recusandae, quaerat excepturi nesciunt quasi consectetur asperiores consequatur at unde repellendus cumque ea? Magni laborum quos molestias.
                        </p>
                    </div>
                    <div class="d-flex justify-content-start align-items-center mt-3">
                        <img class="pe-4" src="../assets/img/theguardian-xsmall.png" alt="">
                        <p class="m-0 fw-medium">Gerald Hendley, The Guardian</p>                            
                    </div>

                    <div class="bg-section p-4 card rounded-0 mt-5 border-0">
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



    .critics{
        margin: 100px 0;
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
    .read:hover{
        width: 280px;
        height: 50px;
    }
</style>