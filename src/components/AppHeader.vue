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

        <div class="ps-5 pe-5">
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
                                <svg xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 576 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M0 24C0 10.7 10.7 0 24 0H69.5c22 0 41.5 12.8 50.6 32h411c26.3 0 45.5 25 38.6 50.4l-41 152.3c-8.5 31.4-37 53.3-69.5 53.3H170.7l5.4 28.5c2.2 11.3 12.1 19.5 23.6 19.5H488c13.3 0 24 10.7 24 24s-10.7 24-24 24H199.7c-34.6 0-64.3-24.6-70.7-58.5L77.4 54.5c-.7-3.8-4-6.5-7.9-6.5H24C10.7 48 0 37.3 0 24zM128 464a48 48 0 1 1 96 0 48 48 0 1 1 -96 0zm336-48a48 48 0 1 1 0 96 48 48 0 1 1 0-96z"/></svg>
                            </a>
                        </li>
                    </ul>
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
    .navigation{
        height: 150px;
    }
    ul{
        list-style: none;
    }
    li{
        padding: 0 1.25rem;
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
    svg{
        fill: white;
    }
</style>