<script>
export default {
    name: 'SectionArticles',
    data() {
        return {
            
        }
    }
}
</script>

<template>

    <section class="articles">

        <div class="container">
            <div class="row">
                
                <div class="col-8">

                    <div class="card bg-transparent border-0">
                        <h2 class="font fs-1 fw-bold m-0">Recent Articles</h2>
                        <h5 class="green fw-medium pt-3 pb-4 m-0">READ THE LATEST ENTRIES</h5>
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
                    <!--articles-->
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



    .articles{
        background-color: $bfg_section;
        padding: 80px 0;
    }
    .read{
        background-color: $yellow;
        width: 240px;
        height: 40px;
    }
</style>