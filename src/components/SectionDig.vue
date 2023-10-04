<script>
export default {
    name: 'SectionDig',
    data() {
        return {
            
        }
    }
}
</script>

<template>
    
    <section class="dig">
            
        <div class="container text-center">
            <h2 class="font fs-1 fw-bold m-0">Dig A Little Deeper Into Damon Vaughn</h2>
            <h5 class="fw-medium pt-3 pb-5 m-0 green">FIND OUT MORE ABOUT AUTHOR HIMSELF</h5>
            <div class="row">
                <div class="col-4 pe-4">
                    <div class="me card border-0">
                        <div class="darkin">
                            <h3 class="text-white pb-3 m-0">About Me</h3>
                            <div class="border-bottom border-dark-subtle mb-4 w-25"></div>
                            <p class="pb-4 m-0 fw-medium yellow">Vestibulum ante ipsum primis</p>
                        </div>
                    </div>
                </div>
                <div class="col-4 pe-4 ps-4">
                    <div class="latest card border-0">
                        <div class="darkin">
                            <h3 class="text-white pb-3 m-0">My Latest Book</h3>
                            <div class="border-bottom border-dark-subtle mb-4 w-25"></div>
                            <p class="pb-4 m-0 fw-medium yellow">Vestibulum ante ipsum primis</p>
                        </div>
                    </div>
                </div>
                <div class="col-4 ps-4">
                    <div class="signing card border-0">
                        <div class="darkin">
                            <h3 class="text-white pb-3 m-0">Book Signing</h3>
                            <div class="border-bottom border-dark-subtle mb-4 w-25"></div>
                            <p class="pb-4 m-0 fw-medium yellow">Vestibulum ante ipsum primis</p>
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



    .dig{
        margin: 100px 0;
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
    .me:hover{
        width: 420px;
        height: 520px;
        box-shadow: 0px 5px 5px 5px rgba(0, 0, 0, 0.360);
    }
    .latest:hover{
        width: 420px;
        height: 520px;
        box-shadow: 0px 5px 5px 5px rgba(0, 0, 0, 0.360);
    }
    .signing:hover{
        width: 420px;
        height: 520px;
        box-shadow: 0px 5px 5px 5px rgba(0, 0, 0, 0.360);
    }
    .darkin:hover{
        width: 420px;
        height: 520px;
    }
</style>