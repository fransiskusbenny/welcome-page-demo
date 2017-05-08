<template>
    <section class="header-bg">
        <div class="container">
            <h1 class="wow fadeIn" 
                data-wow-delay=".5s"
                data-wow-duration="2s">
                Lorem ipsum dolor sit amet, consectetur.</h1>
            <p class="wow fadeIn" 
                data-wow-delay=".7s"
                data-wow-duration="2s">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ut saepe omnis quam.
            </p>
            <div class="col-md-6 col-sm-12 col-md-offset-3">
                <div class="box wow fadeIn"
                    data-wow-delay=".9s"
                    data-wow-duration="2s">
                    <div class="box-icon"><span class="fa fa-4x fa-search"></span></div>
                    <div class="info">
                        <h4 class="text-center">Lorem ipsum dolor</h4>
                        <form>
                            <div class="form-group">
                                <select name="select" id="select" class="form-control">
                                    <option value="for_sale">For Sale</option>
                                    <option value="for_rent">For Rent</option>
                                </select>
                            </div>
                            <div class="form-group">
                                <select name="select" id="select" class="form-control">
                                    <option value="house">House</option>
                                    <option value="apartement">Apartement</option>
                                </select>
                            </div>
                      
                            <div class="form-group"><input type="text" class="form-control" placeholder="Location"></div>
                          
                            <button class="btn btn-primary btn-block btn-search">Search</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
    .box {
        border-radius: 3px;
        background-color: #fff;
        box-shadow: 0 2px 5px 0 rgba(0, 0, 0, 0.16), 0 2px 10px 0 rgba(0, 0, 0, 0.12);
        padding: 10px 25px;
        text-align: right;
        display: block;
        margin-top: 50px;
    }
    .box-icon {
        background-color: #57a544;
        border-radius: 50%;
        display: table;
        height: 100px;
        margin: 0 auto;
        width: 100px;
        margin-top: -60px;
    }
    .box-icon span {
        color: #fff;
        display: table-cell;
        text-align: center;
        vertical-align: middle;
    }
    .info h4 {
        font-size: 20px;
        letter-spacing: 2px;
        text-transform: uppercase;
        color: #000;
    }
</style>