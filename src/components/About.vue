<template>
    <section class="about">
        <div class="container">
            <div class="col-md-7">
                <h3 class="subtitle">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo saepe dignissimos harum iure tempore autem ?
                </h3>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sed rem vel, perferendis cupiditate consequuntur alias amet vitae, consectetur minima beatae eaque facere nisi, nihil deleniti reprehenderit! Odio debitis laboriosam sunt!
                </p>
            </div>
            
            <div class="col-md-5">
                <flickity ref="flickity" 
                    :options="flickityOptions" 
                    class="carousel">
                    <div class="carousel-cell"></div>
                    <div class="carousel-cell"></div>
                    <div class="carousel-cell"></div>
                </flickity>
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
                    wrapAround: true,
                    cellAlign: 'center',
                }
            }
        }
    }
</script>

<style scoped>
    .about {
        margin: 4em 0;
    }
    .about .subtitle {
        font-size: 20px;
        font-weight: 300;
        line-height: 36px;
        color: #7e7e7e;
        margin-top: 20px;
    }
    
    .about p {
        font-size: 15px;
        color: #7e7e7e;
        line-height: 30px
    }
    
    .carousel-cell {
        width: 66%;
        height: 150px;
        margin-right: 10px;
        background: #8C8;
        border-radius: 5px;
        counter-increment: carousel-cell;
    }
</style>