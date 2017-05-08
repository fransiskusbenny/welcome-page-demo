<template>
    <!-- Services -->
    <section class="section section-bg-gray">
        <div class="container">
            <h3 class="title wow fadeInUpBig"
                data-wow-delay=".5s"
                data-wow-duration="1s"
                >
                Our Partners
            </h3>
            <div class="row">
                <div class="partners center-block">
                    <a href="#" class="wow fadeInUp" 
                        data-wow-delay=".7s"
                        data-wow-duration="1.5s"
                    >
                        <img src="../assets/images/partner1.png" style="width: 150px">
                    </a> 
                    <a href="#" 
                        class="wow fadeInUp" 
                        data-wow-delay=".7s"
                        data-wow-duration="1.5s"
                    >
                        <img src="../assets/images/partner2.png" style="width: 130px">
                    </a>
                    <a href="#" 
                        class="wow fadeInUp" 
                        data-wow-delay=".7s"
                        data-wow-duration="1.5s">
                        <img src="../assets/images/partner3.png" style="width: 125px">
                    </a>
                     <a href="#" class="wow fadeInUp" 
                        data-wow-delay=".7s"
                        data-wow-duration="1.5s">
                        <img src="../assets/images/partner4.png" style="width: 130px">
                    </a>
                     <a href="#"
                        class="wow fadeInUp" 
                        data-wow-delay=".7s"
                        data-wow-duration="1.5s">
                        <img src="../assets/images/partner5.png" style="width: 125px">
                    </a>
                    <a href="#"
                        class="wow fadeInUp" 
                        data-wow-delay=".7s"
                        data-wow-duration="1.5s">
                        <img src="../assets/images/partner6.png" style="width: 120px">
                    </a> 
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>

    .partners {
        max-width: 800px;
        text-align: center; 
    }
    
    .partners a, .partners img {
        width: 100px;
        display: inline-block;
        vertical-align: middle;
    }
    
    .partners img {
        opacity: 0.66;
        filter: grayscale(100%);
        transition: all 0.3s ease;
    }
    
    .partners a {
        position: relative;
        margin: 20px 0;
        margin-right: 4em;
    }
    
    .partners img:hover {
        filter: none;
        opacity: 1;
    }
</style>