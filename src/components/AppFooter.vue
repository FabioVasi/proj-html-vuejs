<script>
export default {
    data() {
        return {
            name: 'AppFooter'
        }
    }
}
</script>

<template>

    <footer id="footer_app">

        <div class="d-flex justify-content-between align-items-center">
    
            <div class="col-2">
                <div class="card border-0 bg-transparent ps-5 d-flex justify-content-between align-items-center">
                    <img width="150px" src="../assets/img/author-logo-round.png" alt="">
                </div>
            </div>
            <div class="col-10">
                <div class="row">
                    <div class="col 4">
                        
                    </div>
                    <div class="col 4">
                        
                    </div>
                    <div class="col 4">
                        
                    </div>
                </div>
            </div>
                    
        </div>

        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="card border-0 bg-transparent">
                        
                    </div>
                </div>
            </div>
        </div>

    </footer>

</template>



<style lang="scss" scoped>
    @use '../assets/scss/partials/variables.scss' as *;

    #footer_app{
        background-image: url(../assets/img/footer-3.jpg);
        background-size: cover;
        padding-top: 100px;
        padding-bottom: 50px;
    }
</style>