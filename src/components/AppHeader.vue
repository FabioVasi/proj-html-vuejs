<script>
export default {
    data() {
        return {
            name: 'AppHeader'
        }
    }
}
</script>

<template>

    <header id="header_app">

        <div class="pseudo_container">
            <div class="navigation d-flex justify-content-between">
                <div>
                    <img src="../assets/img/author-logo-round-200x205.png" alt="">
                </div>
                
                <div class="navbar p-0">
                    <ul class="d-flex justify-content-evenly p-0">
                        <li>
                            <a class="active" href="#">Home</a>
                        </li>
                        <li>
                            <a href="#">About Me</a>
                        </li>
                        <li>
                            <a href="#">Testimonials</a>
                        </li>
                        <li>
                            <a href="#">My Blog</a>
                        </li>
                        <li>
                            <a href="#">Meetups</a>
                        </li>
                        <li>
                            <a href="#">Shop</a>
                        </li>
                        <li>
                            <a href="#">Contact Me</a>
                        </li>
                        <li>
                            <a href="#">
                                <svg class="icon" xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 576 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M0 24C0 10.7 10.7 0 24 0H69.5c22 0 41.5 12.8 50.6 32h411c26.3 0 45.5 25 38.6 50.4l-41 152.3c-8.5 31.4-37 53.3-69.5 53.3H170.7l5.4 28.5c2.2 11.3 12.1 19.5 23.6 19.5H488c13.3 0 24 10.7 24 24s-10.7 24-24 24H199.7c-34.6 0-64.3-24.6-70.7-58.5L77.4 54.5c-.7-3.8-4-6.5-7.9-6.5H24C10.7 48 0 37.3 0 24zM128 464a48 48 0 1 1 96 0 48 48 0 1 1 -96 0zm336-48a48 48 0 1 1 0 96 48 48 0 1 1 0-96z"/></svg>
                            </a>
                        </li>
                    </ul>
                </div>                
            </div>
        </div>

        <div class="author text-white d-flex flex-wrap">
            <div class="col-6">
                <div>
                    <h2>Damon Vaughn</h2>
                    <h3>
                        Best-selling author and the most influential public intellectual in the western world right now.
                    </h3>
                    <p class="editor">- The New York Times</p>
                    <div class="navigator d-flex">
                        <div class="prev">
                            <svg class="arrow icon" xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M9.4 233.4c-12.5 12.5-12.5 32.8 0 45.3l160 160c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L109.2 288 416 288c17.7 0 32-14.3 32-32s-14.3-32-32-32l-306.7 0L214.6 118.6c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0l-160 160z"/></svg>
                        </div>
                        <div class="next">
                            <svg class="arrow" xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M438.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L338.8 224 32 224c-17.7 0-32 14.3-32 32s14.3 32 32 32l306.7 0L233.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160z"/></svg>
                        </div>
                    </div>
                </div>               
            </div>

            <div class="col-6">
                <div class="squares me-4">
                    <div class="sales card mb-2 d-flex justify-content-center align-items-center">
                        <svg style="font-size: 24px;" xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 576 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M88.7 223.8L0 375.8V96C0 60.7 28.7 32 64 32H181.5c17 0 33.3 6.7 45.3 18.7l26.5 26.5c12 12 28.3 18.7 45.3 18.7H416c35.3 0 64 28.7 64 64v32H144c-22.8 0-43.8 12.1-55.3 31.8zm27.6 16.1C122.1 230 132.6 224 144 224H544c11.5 0 22 6.1 27.7 16.1s5.7 22.2-.1 32.1l-112 192C453.9 474 443.4 480 432 480H32c-11.5 0-22-6.1-27.7-16.1s-5.7-22.2 .1-32.1l112-192z"/></svg>
                        <p class="mt-1 mb-0 fw-medium">Demos</p>
                    </div>
                    <div class="sales card d-flex justify-content-center align-items-center">
                        <div style="color: #49a987;" class="fs-2 fw-medium m-0 d-flex justify-content-center align-items-center"><p class="fs-5 pb-2 m-0">$</p>39</div>
                        <p class="m-0">On Sale</p>
                    </div>
                </div>

                <div class="advertising">

                </div>
            </div>
        </div>
            
    </header>

</template>

<style lang="scss" scoped>
    @use '../assets/scss/partials/variables.scss' as *;

    #header_app{
        background-image: url(../assets/img/hero-07-2x.jpg);
        background-size: cover;
        height: 800px;
    }
    .pseudo_container{
        padding: 0 6rem;
    }
    .navigation{
        height: 150px;
    }
    ul{
        list-style: none;
    }
    li{
        padding: 0 1rem;
    }
    .active{
        color: $yellow;
        border-top: 4px solid $yellow;
    }
    a{
        text-decoration: none;
        color: white;
        font-size: 20px;
        font-weight: 500;
        padding: 3rem 0;
    }
    .icon{
        fill: white;
    }
    .author{
        margin-top: 150px;
        margin-left: 10%;
    }
    h2{
        color: $yellow;
        font-size: 5rem;
        font-family: 'Times New Roman', Times, serif;
        font-style: oblique;
        font-weight: bold;
    }
    h3{
        font-size: 3rem;
        font-weight: bold;
        font-family: 'Times New Roman', Times, serif;
    }
    .editor{
        color: $light-grey;
        font-size: 20px;
        font-family: 'Times New Roman', Times, serif;
        font-style: oblique;
        margin-bottom: 2rem;
    }
    .prev, .next {
        background-color: rgba(5, 5, 5, 0.8);
        padding: 10px;
        margin: 2px;
        height: 48px;
        width: 48px;
        display: flex;
        justify-content: center;
        align-items: center;
        cursor: pointer;
    }
    .squares{
        display: flex;
        flex-direction: column;

        align-items: end;
    }
    .sales{
        width: 80px;
        height: 80px;
    }
</style>