<template>
    <section class="section popular">
        <div class="container">
            <h3 class="title-2 wow fadeIn">Popular Properties</h3>
        </div>
        <div class="most-popular">
            <flickity ref="flickity" :options="flickityOptions" class="carousel">
                <div class="carousel-cell">
                   <div class="popular-card wow fadeIn">
                        <img src="../assets/images/home1.jpg" class="img-responsive img-carousel img-rounded"/>
                   </div>
                   <div class="popular-card wow fadeIn">
                        <img src="../assets/images/home2.jpg" class="img-responsive img-carousel img-rounded"/>
                   </div>
                </div>
                <div class="carousel-cell">
                    <div class="popular-card wow fadeIn">
                        <img src="../assets/images/home3.jpg" class="img-responsive img-carousel img-rounded"/>
                    </div>
                    <div class="popular-card wow fadeIn">
                        <img src="../assets/images/home4.jpg" class="img-responsive img-carousel img-rounded"/>
                    </div>
                </div>
                <div class="carousel-cell">
                    <div class="popular-card wow fadeIn">
                        <img src="../assets/images/home5.jpg" class="img-responsive img-carousel img-rounded"/>
                    </div>
                    
                    <div class="popular-card wow fadeIn">
                        <img src="../assets/images/home6.jpg" class="img-responsive img-carousel img-rounded"/>
                    </div>
                </div>
                <div class="carousel-cell">
                    <div class="popular-card wow fadeIn">
                        <img src="../assets/images/home7.jpg" class="img-responsive img-carousel img-rounded"/>
                    </div>
                    <div class="popular-card wow fadeIn">
                        <img src="../assets/images/home8.jpg" class="img-responsive img-carousel img-rounded"/>
                    </div>
                </div>
                <div class="carousel-cell">
                    <div class="popular-card wow fadeIn">
                        <img src="../assets/images/home9.jpg" class="img-responsive img-carousel img-rounded"/>
                    </div>
                    
                    <div class="popular-card wow fadeIn">
                        <img src="../assets/images/home10.jpg" class="img-responsive img-carousel img-rounded"/>
                    </div>
                </div>
            </flickity>
            <div class="text-center show-more">
                <a href="#" class="show-more text-muted">Show More</a>
            </div>
        </div>
    </section>
</template>

<script>
    import Flickity from 'vue-flickity'
    
    export default {
        components: {
            Flickity,
        },
        
        data() {
            return {
                flickityOptions: {
                    freeScroll: true,
                    pageDots: false,
                    wrapAround: true,
                    autoPlay: 1500,
                    cellAlign: 'center',
                    setGallerySize: false,
                    prevNextButtons: false,
                }
            }
        }
    }
</script>

<style> 
    .most-popular {
        margin-top: 2em;
    }
    .carousel {
        padding-bottom: 30px;
    }
    
    .flickity-viewport {
        position: relative;
        width: 100%;
        height: 500px;
    }
    .carousel-cell {
        width: 358px; 
        height: auto;
        margin-right: 17px;
    }
    .img-carousel {
        padding-bottom: 17px;
        opacity: 0.8;
    }
    
    .carousel .popular-card+ .popular-card {
        left: -70px;
        position: relative;
        margin-bottom: 13px;
    }
    
    .show-more > a {
        font-size: 100%;
        font-weight: 600;
        text-transform: uppercase;
    }
    
    .show-more > a:hover {
        text-decoration: none;
        color: #4d545d;
    }
</style>