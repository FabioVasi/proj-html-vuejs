<script>
export default {
    name: 'SectionUpcoming',
    data() {
        return {
            
        }
    }
}
</script>

<template>

    <section class="upcoming">
        <!--upcoming-->
        <div class="container text-center">
            <h2 class="font fs-1 fw-bold m-0">Upcoming Events</h2>
            <h5 class="yellow fw-medium pt-3 pb-5 m-0">MEET THE AUTHOR IN PERSON</h5>

            <div class="row g-5">

                <div class="col-4">
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
                
                <div class="col-4">
                    <div class="card border-0 rounded-0">
                        <img src="../assets/img/event-04-400x240.jpg" class="card-img-top rounded-0" alt="">
                        <div class="card-body p-4">
                            <h4 class="card-title border-bottom pb-4">Meet & Greet With Amanda</h4>
                            <p class="card-text">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat sint dignissimos sunt quibusdam sed nihil at eum eos, quos, unde id vitae natus obcaecati fugit molestias enim magni laudantium totam.
                            </p>
                        </div>
                    </div>
                </div>

                <div class="col-4">
                    <div class="card border-0 rounded-0">
                        <img src="../assets/img/event-07-400x240.jpg" class="card-img-top rounded-0" alt="">
                        <div class="card-body p-4">
                            <h4 class="card-title border-bottom pb-4">Open Book: Dialogues</h4>
                            <p class="card-text">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat sint dignissimos sunt quibusdam sed nihil at eum eos, quos, unde id vitae natus obcaecati fugit molestias enim magni laudantium totam.
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


    
    .upcoming{
        background-color: $bfg_section;
        padding: 80px 0;
    }
    .card:hover{
        filter: opacity(0.8);
    }
</style>