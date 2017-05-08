<template>
    <div class="section contact">
        <div class="container">
            <div class="row wow fadeInRight"  data-wow-delay=".5s" data-wow-duration="1s">
                <div class="heading">
                    <h3 class="title-2">Get In Touch</h3>
                    <p class="center-block">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum neque soluta asperiores, et suscipit laudantium sunt iure expedita veritatis libero explicabo minima, quam beatae dicta, aliquid sint accusantium autem illo.
                    </p>
                </div>
            </div>
            <div class="row wow fadeInLeft" data-wow-delay=".7s" data-wow-duration="1s">
                <div class="col-md-6 col-sm-12">
                    <div class="contact-address">
                         <h4>Contact Address</h4>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maxime sequi fugit corporis neque, aut libero nulla ipsa illum quia at sed recusandae, nesciunt porro, ipsum! Dolore omnis quia perferendis dolor.
                        </p>
                    </div>
                    <address>
                        <hr>
                        <p>
                            Lorem ipsum,
                            <br>
                            Lorem,
                            <br>
                            Consectetur
                        </p>
                        <hr>
                        <p>
                            <strong>Email : </strong>&nbsp;email@example.com <br>
                            <strong>CP : </strong>&nbsp;+6821-8689-5060 <br>
                        </p>
                    </address>
                </div>
                
                <div class="col-md-5 col-md-offset-1 col-sm-12">
                    <form>
                        <div class="form-group">
                            <input type="text" class="form-control input-lg" 
                                placeholder="Your name" required>
                        </div>
                        <div class="form-group">
                            <input type="email" class="form-control input-lg" 
                                placeholder="Email Address" required>
                        </div>
                        <div class="form-group">
                            <textarea name="message" id="message" cols="30" rows="5" class="form-control input-lg" placeholder="Your message"></textarea>
                        </div>
                        
                        <button class="btn btn-primary btn-block btn-lg">
                            Contact us
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .heading p {
        text-align: center;
        font-size: 14px;
        font-weight: 300;
        line-height: 30px;
        max-width: 800px;
        margin-bottom: 3em;
    }
    
    .contact-address h4 {
        font-size: 25px;
        font-weight: 200;
        margin-bottom: 1em;
    }
    
    .contact-address p {
        line-height: 25px;
        font-size: 13px;
        margin-bottom: 2em;
    }
    
    address p {
        font-size: 14px;
        line-height: 30px;
        margin-bottom: 2em;
    }
</style>