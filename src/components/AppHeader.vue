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

        <div class="author d-flex flex-wrap">
            <div class="col-6 mt-5">
                <div class="mt-5">
                    <h2 class="">Damon Vaughn</h2>
                    <h3 class="best-seller text-white">
                        Best-selling author and the most influential public intellectual in the western world right now.
                    </h3>
                    <p class="editor">- The New York Times</p>
                    <div class="navigator d-flex">
                        <div class="prev">
                            <svg class="arrow icon" xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M9.4 233.4c-12.5 12.5-12.5 32.8 0 45.3l160 160c12.5 12.5 32.8 12.5 45.3 0s12.5-32.8 0-45.3L109.2 288 416 288c17.7 0 32-14.3 32-32s-14.3-32-32-32l-306.7 0L214.6 118.6c12.5-12.5 12.5-32.8 0-45.3s-32.8-12.5-45.3 0l-160 160z"/></svg>
                        </div>
                        <div class="next">
                            <svg class="arrow icon" xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M438.6 278.6c12.5-12.5 12.5-32.8 0-45.3l-160-160c-12.5-12.5-32.8-12.5-45.3 0s-12.5 32.8 0 45.3L338.8 224 32 224c-17.7 0-32 14.3-32 32s14.3 32 32 32l306.7 0L233.4 393.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0l160-160z"/></svg>
                        </div>
                    </div>
                </div>               
            </div>

            <div style="padding-left: 150px;" class="col-6">
                <div class="squares me-4 mb-5">
                    <div class="sales card mb-2 d-flex justify-content-center align-items-center">
                        <svg style="font-size: 24px;" xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 576 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M88.7 223.8L0 375.8V96C0 60.7 28.7 32 64 32H181.5c17 0 33.3 6.7 45.3 18.7l26.5 26.5c12 12 28.3 18.7 45.3 18.7H416c35.3 0 64 28.7 64 64v32H144c-22.8 0-43.8 12.1-55.3 31.8zm27.6 16.1C122.1 230 132.6 224 144 224H544c11.5 0 22 6.1 27.7 16.1s5.7 22.2-.1 32.1l-112 192C453.9 474 443.4 480 432 480H32c-11.5 0-22-6.1-27.7-16.1s-5.7-22.2 .1-32.1l112-192z"/></svg>
                        <p class="mt-1 mb-0 fw-medium">Demos</p>
                    </div>
                    <div class="sales card d-flex justify-content-center align-items-center">
                        <div style="color: #49a987;" class="fs-2 fw-medium m-0 d-flex justify-content-center align-items-center"><p class="fs-5 pb-2 m-0">$</p>39</div>
                        <p class="mb-1 fw-medium">On Sale</p>
                    </div>
                </div>

                <div style="background-color: #ffffff;" class="advertising p-5">
                    <div class="d-flex flex-wrap">
                        <div class="col-6">
                            <img src="../assets/img/book-widget.png" alt="">
                        </div>
                        <div class="col-6">
                            <h3 style="font-family: 'Times New Roman', Times, serif; color: #333333;" class="fs-2 fw-bold">Latest Book Release</h3>
                            <h5 style="color: #f4b429;">D. VAUGHN AUTOBIOGRAPHY</h5>
                            <span style="color: #333333;" class="fs-5 d-inline-block mt-2">Vestibulum tristique turpis in ipsum egestas lobortis. Duis maximus bibendum volutpat. Lorem ipsum dolor sit amet</span>
                        </div>
                    </div>
                    
                    <div class="col-12 text-center">
                        <div class="btn-group" role="group">
                            <button type="button" class="btn left d-flex justify-content-center align-items-center">
                                <svg style="font-size: 20px;" xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M257.2 162.7c-48.7 1.8-169.5 15.5-169.5 117.5 0 109.5 138.3 114 183.5 43.2 6.5 10.2 35.4 37.5 45.3 46.8l56.8-56S341 288.9 341 261.4V114.3C341 89 316.5 32 228.7 32 140.7 32 94 87 94 136.3l73.5 6.8c16.3-49.5 54.2-49.5 54.2-49.5 40.7-.1 35.5 29.8 35.5 69.1zm0 86.8c0 80-84.2 68-84.2 17.2 0-47.2 50.5-56.7 84.2-57.8v40.6zm136 163.5c-7.7 10-70 67-174.5 67S34.2 408.5 9.7 379c-6.8-7.7 1-11.3 5.5-8.3C88.5 415.2 203 488.5 387.7 401c7.5-3.7 13.3 2 5.5 12zm39.8 2.2c-6.5 15.8-16 26.8-21.2 31-5.5 4.5-9.5 2.7-6.5-3.8s19.3-46.5 12.7-55c-6.5-8.3-37-4.3-48-3.2-10.8 1-13 2-14-.3-2.3-5.7 21.7-15.5 37.5-17.5 15.7-1.8 41-.8 46 5.7 3.7 5.1 0 27.1-6.5 43.1z"/></svg>
                                <p class="m-0 fs-5 fw-medium ps-2">Buy On Amazon</p>
                            </button>
                            <button type="button" class="btn right d-flex justify-content-center align-items-center">
                                <svg style="font-size: 20px;" xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 384 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M318.7 268.7c-.2-36.7 16.4-64.4 50-84.8-18.8-26.9-47.2-41.7-84.7-44.6-35.5-2.8-74.3 20.7-88.5 20.7-15 0-49.4-19.7-76.4-19.7C63.3 141.2 4 184.8 4 273.5q0 39.3 14.4 81.2c12.8 36.7 59 126.7 107.2 125.2 25.2-.6 43-17.9 75.8-17.9 31.8 0 48.3 17.9 76.4 17.9 48.6-.7 90.4-82.5 102.6-119.3-65.2-30.7-61.7-90-61.7-91.9zm-56.6-164.2c27.3-32.4 24.8-61.9 24-72.5-24.1 1.4-52 16.4-67.9 34.9-17.5 19.8-27.8 44.3-25.6 71.9 26.1 2 49.9-11.4 69.5-34.3z"/></svg>
                                <p class="m-0 fs-5 fw-medium ps-2">Buy On AppStore</p>
                            </button>
                        </div>
                    </div>

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
        border-bottom: 1px solid black;
        box-shadow: 0px -20px 600px 10px rgb(0, 0, 0) inset;
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
        margin-left: 10%;
        position: absolute;
        bottom: 483px;
        right: 0;
    }
    h2{
        color: $yellow;
        font-size: 5rem;
        font-family: 'Times New Roman', Times, serif;
        font-style: oblique;
        font-weight: bold;
    }
    .best-seller{
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
    .advertising{
        
    }
    .btn-group{
        border: 2px solid $green;
    }
    .btn{
        background-color: #49a98720;
        width: 280px;
        height: 50px;
    }
</style>