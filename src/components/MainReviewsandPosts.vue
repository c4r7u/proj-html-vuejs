<template>
   <main>
       <div class="box-center">
           <div class="feature">
                <div class="images">
                    <img class="butter" src="../assets/images/shaving_butter.png" alt="">
                </div>
                <div class="info-feature">
                    <span class="s-feature">THIS MONTHS FEATURED PRODUCT</span>
                    <h4 class="h-feature">Shaving Butter</h4>
                    <p class="p-feature">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque laoreet enim est, vel molestie dolor ultrices ut. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                    <a class="a-button" href="#">BUY NOW</a>
                </div>
           </div>
       </div>
       <div class="reviews">
           <div class="head-reviews">
               <span class="s-feature">WHAT PEOPLE SAY</span>
               <h4 class="h-feature">Reviews</h4>
           </div>
           <div class="info-reviews">
               <div class="box">
                   <p class="p-feature">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi mollis eleifend ante ut sagittis. Sed sodales, urna et imperdiet placerat, ex nisi aliquam orci, ac varius odio libero et arcu.</p>
                   <img class="img" src="../assets/images/avadabarbers-trimcut-gallery6.jpg" alt="">
                   <span class="s-feature">John Doe</span>
               </div>
               <div class="box">
                   <p class="p-feature">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi mollis eleifend ante ut sagittis. Sed sodales, urna et imperdiet placerat, ex nisi aliquam orci, ac varius odio libero et arcu.</p>
                   <img class="img" src="../assets/images/avadabarbers-trimcut-gallery7.jpg" alt="">
                   <span class="s-feature">Pete Jones</span>
               </div>
               <div class="box">
                   <p class="p-feature">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi mollis eleifend ante ut sagittis. Sed sodales, urna et imperdiet placerat, ex nisi aliquam orci, ac varius odio libero et arcu.</p>
                   <img class="img" src="../assets/images/avadabarbers-trimcut-gallery3.jpg" alt="">
                   <span class="s-feature">Mark Wilson</span>
               </div>
           </div>
       </div>
       <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#f5f5f5" fill-opacity="1" d="M0,32L720,288L1440,32L1440,320L720,320L0,320Z"></path></svg>

       <div class="reviews">
           <div class="head-reviews">
               <span class="s-feature">TALES FROM THE BARBER SHOP</span>
               <h4 class="h-feature">Recent Blog Posts</h4>
           </div>
           <div class="info-posts">
               <div class="box">
                   <img class="posts-images" src="../assets/images/avadabarbers-second-blog-700x441.jpg" alt="">
                   <h4 class="h-posts">Avada Barbers Now Open</h4>
                   <p class="p-feature">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ut dapibus magna. Praesent semper,</p>
               </div>
               <div class="box">
                   <img class="posts-images" src="../assets/images/avadabarbers-choosing-blog-700x441.jpg" alt="">
                   <h4 class="h-posts">Choosing The Right Barber</h4>
                   <p class="p-feature">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ut dapibus magna. Praesent semper,</p>
               </div>
               <div class="box">
                   <img class="posts-images" src="../assets/images/avadabarbers-ourservice-blog-700x441.jpg" alt="">
                   <h4 class="h-posts">Quick Service Guide</h4>
                   <p class="p-feature">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ut dapibus magna. Praesent semper,</p>
               </div>
           </div>
           <div class="width">
               <a class="posts-button" href="#">READ MORE FROM OUR BLOG</a>
           </div>
       </div>
   </main>
</template>

<script>
export default {
    name: 'MainReviewsandPosts',
};
</script>

<style lang="scss" scoped>
.box-center {
    display: flex;
    justify-content: center;
}


.feature {
    height: 270px;
    width: 650px;
    background-color: #121413;
    margin-top: -50px;
    display: flex;
    border-top: 5px solid #be9359;
}

.images {
    float: left;
    width: 280px;
    background-image: url(../assets/images/avadabarbers-cta-background.jpg);
    background-size: cover;
}

.butter {
    height: 250px;
    margin-left: 20px;
}

.info-feature {
    height: 230px;
    width: 300px;
    position: relative;
    top: 30px;
    left: 30px;
}

.s-feature {
    color: #be9359;
    font-size: 12px;
    display: block;
}

.h-feature {
    color: #b1b1b1;
    font-size: 40px;
    margin-top: 10px;
}

.p-feature {
    color: #b1b1b1;
    font-size: 12px;
    margin-top: 20px;
}

.a-button {
    text-decoration: none;
    color: #be9359;
    padding: 10px 15px;
    border: 1px solid #be9359;
    font-size: 13px;
}

.reviews {
    height: 700px;
}

.head-reviews {
    text-align: center;
    width: 100%;
    margin-top: 50px;
}

.info-reviews {
    width: 100%;
    display: flex;
    justify-content: center;
    margin-top: 250px;
}

.box {
    height: 400px;
    width: 300px;
    margin: 0px 30px;
    text-align: center;
}

.img {
    height: 100px;
    margin-top: 30px;
    border-radius: 50%;
    margin-bottom: 30px;
}

.posts {
    height: 600px;
    background-color: #f5f5f5;
}

.info-posts {
    width: 100%;
    display: flex;
    justify-content: center;
}

.posts-images {
    width: 100%;
    margin-bottom: 20px;
}

.h-posts {
    color: #be9359;
    font-size: 30px;
}

.width {
    width: 100%;
    display: flex;
    justify-content: center;
}

.posts-button {
    font-size: 13px;
    border: 1px solid #be9359;
    color: #be9359;
    padding: 13px 10px;
    text-decoration: none;
    align-self: center;
}

</style>