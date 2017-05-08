<template>
    <footer class="text-muted footer">
        <div class="container">
            <div class="row">
                <div class="col-sm-12">
                    <h2 class="footer-title wow swing"
                        data-wow-delay=".5s"
                        data-wow-duration=".5s">Lorem ipsum dolor sit amet.</h2>
                </div>
            </div>
            <div class="row">
                <div class="col-md-8">
                    <div class="row">
                        <div class="col-md-4 wow jello" 
                            data-wow-delay=".5s"
                            data-wow-duration="1s">
                            <h5 class="footer-header">Heading</h5>
                            <ul class="list-unstyled">
                                <li><a href="#">lorem</a></li>
                                <li><a href="#">lorem</a></li>
                                <li><a href="#">lorem</a></li>
                                <li><a href="#">lorem</a></li>
                            </ul>
                        </div>
                        
                        <div class="col-md-4 wow jello" 
                            data-wow-delay=".5s"
                            data-wow-duration="1s">
                            <h5 class="footer-header">Heading</h5>
                            <ul class="list-unstyled">
                                <li><a href="#">lorem</a></li>
                                <li><a href="#">lorem</a></li>
                                <li><a href="#">lorem</a></li>
                                <li><a href="#">lorem</a></li>
                            </ul>
                        </div>
                        
                        <div class="col-md-4 wow jello" 
                            data-wow-delay=".5s"
                            data-wow-duration="1s">
                            <h5 class="footer-header">Heading</h5>
                            <ul class="list-unstyled">
                                <li><a href="#">lorem</a></li>
                                <li><a href="#">lorem</a></li>
                                <li><a href="#">lorem</a></li>
                                <li><a href="#">lorem</a></li>
                            </ul>
                        </div>
                      </div>
                </div>
                
                <div class="col-md-4 wow bounceInRight" 
                            data-wow-delay=".5s"
                            data-wow-duration="1s" >
                    <p class="footer-description">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Odit nesciunt, dolor non sit cumque? Delectus vero quasi sequi reiciendis, ad?
                    </p>
                    <ul class="footer-social">
                        <li>
                            <a href="#"><i class="fa fa-facebook fa-2x"></i></a>
                        </li>
                        <li>
                            <a href="#"><i class="fa fa-instagram fa-2x"></i></a>
                        </li>
                        <li>
                            <a href="#"><i class="fa fa-youtube fa-2x"></i></a>
                        </li>
                        <li>
                            <a href="#"><i class="fa fa-twitter fa-2x"></i></a>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="row">
                <div class="col-sm-12">
                    <p class="text-left copy-right">
                        &copy; Company 2017. All rights reserved
                    </p>
                </div>
            </div>
        </div>
    </footer>
</template>

<style scoped>
    .footer {
        background-color: #222;
        font-weight: 400;
    }
    
    .footer-title {
        font-size: 25px;
        text-align: center;
        margin-top: 2em;
        margin-bottom: 2.5em;
    }
    
    .footer-header {
        text-transform: uppercase;
        font-size: 18px;
        margin-bottom: 1em;
    }
    
    .footer ul > li {
        line-height: 2em;
    }
    
    .footer-description {
        letter-spacing: 1.5px;
        font-size: 13px;
        text-align: justify;
        margin-bottom: 4em;
    }
    
    .footer-social {
        list-style: none;
        padding-left: 0;
    }
    
    .footer-social li {
        float: left;
        padding-right: 20px;
    }
    
    .footer-social li > a {
        color: #fff;
    }
    
    .copy-right {
        margin-top: 2em;
        margin-bottom: 3em;
    }
</style>