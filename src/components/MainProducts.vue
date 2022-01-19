<template>
   <main>
       <div class="products">
           <div class="head-products">
               <span class="covered">WE HAVE YOU COVERED</span>
               <h4 class="head-title">Avada Grooming Products</h4>
           </div>
           <div class="info-products">
               <div class="box">
                   <div class="width">
                       <img class="products-img" src="../assets/images/brush_dark.png" alt="">
                   </div>
                   <h6 class="info-title">Brush</h6>
                   <div class="prize">$15.00</div>
               </div>
               <div class="box">
                   <div class="width">
                       <img class="products-img" src="../assets/images/scissors.png" alt="">
                   </div>
                   <h6 class="info-title">Scissors</h6>
                   <div class="prize">$85.00</div>
               </div>
               <div class="box">
                   <div class="width">
                       <img class="products-img" src="../assets/images/hot_oil_dark.png" alt="">
                   </div>
                   <h6 class="info-title">Hot Oil</h6>
                   <div class="prize">$15.00</div>
               </div>
               <div class="box">
                   <div class="width">
                       <img class="products-img" src="../assets/images/straight_razor_dark.png" alt="">
                   </div>
                   <h6 class="info-title">Straight Razor</h6>
                   <div class="prize">$30.00</div>
               </div>
           </div>

           <div class="width">
               <a class="product-button" href="#">SHOP OUR PRODUCT RANGE</a>
           </div>
       </div>
   </main>
</template>

<script>
export default {
    name: 'MainProducts',
};
</script>

<style lang="scss" scoped>
.products {
    height: 750px;
    background-image: url(../assets/images/bg.jpg);
    background-size: cover;
}

.head-products {
    text-align: center;
    width: 100%;
}

.covered {
    color: #be9359;
}

.head-title {
    font-size: 40px;
    margin-top: 15px;
    color: #b1b1b1;
}

.info-products {
    width: 100%;
    display: flex;
    justify-content: center;
    margin-top: 50px;
}

.box {
    height: 400px;
    width: 300px;
    margin: 0px 30px;
}

.width {
    width: 100%;
    display: flex;
    justify-content: center;
}

.products-img {
    height: 250px;
}

.info-title {
    color: #be9359;
    font-size: 25px;
    text-align: center;
    width: 100%;
    margin-top: 40px;
}

.prize {
    color: #be9359;
    font-size: 12px;
    text-align: center;
    width: 100%;
}

.product-button {
    font-size: 13px;
    border: 1px solid #be9359;
    color: #be9359;
    padding: 13px 10px;
    text-decoration: none;
    align-self: center;
}
</style>