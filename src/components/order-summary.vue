<template>
    <div id="order-summary-template">
        <div class="backdrop">
            <div class="container">
                <div class="content">
                    <div class="header-image">
                        <img src="../assets/images/illustration-hero.svg" alt="">
                    </div>
                    <div class="plan-content">
                        <div class="title">
                            Order Summary
                        </div>
                        <div class="description">
                            You can now listen to millions of songs, audiobooks, and podcasts on any 
                            device anywhere you like!
                        </div>
                        <div class="plan">
                            <div class="plan-container">
                                <div class="">
                                    <img src="../assets/images/icon-music.svg" alt="">
                                </div>
                                <div class="plan-infos">
                                    <p class="plan-title">Annual Plan</p>
                                    <p class="plan-price">$59.99/year</p>
                                </div>
                                <div class="plan-cancel">
                                    <a href="#">Change</a>
                                </div>
                            </div>
                        </div>
                        <div class="plan-payment">
                            <button class="btn-payment">Proceed to Payment</button>
                        </div>
                        <div class="plan-cancel-order">
                            Cancel Order
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>

.backdrop{
    background: url(../assets/images/pattern-background-desktop.svg);
    background-repeat: no-repeat;
    background-size: 100%;

}

.container{ 
    height: 500px;
}

.container .plan-content{
    padding: 40px 55px;
}

.content{
    border-radius: 20px;
    width: 450px;
    background-color: #fff;
    position: absolute;
    margin-top: 70px;
    left: 50%;
    transform: translate(-50%);
}

.content .header-image img{
    border-radius: 20px 20px 0 0;
}
/*
.content>div:not(.header-image){
    padding: 10px 45px;
}
*/

.description{
    color: #3d4a78;
    line-height: 1.8;
}

.content .title{
    /*margin-top: 25px;*/
    font-size: 1.8em;
    font-weight: bold;
    color: #374672;
    padding-bottom: 20px;
}

.container .plan{
    text-align: start;
    padding: 25px 0;
}

.container .plan-container{
    display: grid;
    grid-template-columns: 25% 50% 25%;
    align-items: center;
    background-color: #eff7fd;
    padding: 15px;
    border-radius: 5px;
}

.container p{
    padding: 3px 0;
    margin: 0;    
}

.container p.plan-title{
    font-weight: 700;
}

.container p.plan-price{
    color: #4b5c99;
}

.container .plan-cancel{
    color: #4e4fd3;
    font-weight: 600;
}

.container .plan-payment{
    padding-bottom: 25px;
}

.container .btn-payment{
    background-color: #382AE1;
    border: none;
    border-radius: 10px;
    color: #fff;
    padding: 10px 0;
    font-weight: 800;
    width: 90%;
    box-shadow: 0px 15px 15px 0px #c5e7ff;
}

.container .plan-cancel-order{
    color: #656c78;
    font-weight: 700;
}

@media (max-width: 500px) {
    .content{
        width: 90%;
        margin-top: 15px;
    }

    .content .header-image img{
        width: 100%;
    }

    .container .plan-content[data-v-bc5d8672] {
        padding: 40px 5px;
    }
}

@media (max-height: 600px) {
    .content{
        font-size: .8em;
    }
}

</style>