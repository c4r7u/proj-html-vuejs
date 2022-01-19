<template>
    <header>
        <div class="margin-navbar">
            <nav class="navbar">
                <div class="container-fluid">
                    <a class="navbar-brand" href="#">
                        <img class="d-inline-block align-text-top" src="../assets/images/avadabarbers-logo-x1.png" alt="">
                    </a>
                    <form class="d-flex">
                        <a class="btn form-control my-style" href="#"><i class="fas fa-shopping-cart"></i></a>
                        <a class="btn my-style" href="#"><i class="fas fa-bars"></i></a>
                    </form>
                </div>
            </nav>
        </div>
        <div class="banners">
            <div>
                <img src="../assets/images/demos.jpeg" alt="">
            </div>
            <div>
                <img src="../assets/images/onsale.jpeg" alt="">
            </div>
        </div>
        <div class="jumbotron">
            <div class="presentation-shop">
                <h2 class="shop-name">Barber Shop</h2>
                <div class="separator"></div>
                <span class="my-color">The Pinnacle of Male Grooming</span>
                <a class="button" href="#">Learn More</a>
            </div>
            
            <div class="image">
                <img src="../assets/images/avadabarbers_hero_focalmirror.png" alt="">
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: 'Header',
};
</script>





<style lang="scss" scoped>
@import '../styles/general.scss';






header {
    height: 600px;
    background-image: url(../assets/images/avadabarbers-homepage-hero-bg.jpg);
    background-repeat: no-repeat;
    background-size: 100%;
}

.margin-navbar {
    margin: 0px 200px;
}

a img {
    width: 100px;
}

.my-style {
    color: white;
}

.my-style:hover {
    color: white;
}

.banners {
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    margin-right: 10px;
}

.banners img {
    margin-top: 10px;
    height: 40px;
    border-radius: 8px;
}

.jumbotron {
    display: flex;
    justify-content: center;
}

.shop-name {
    font-family: 'Pacifico', sans-serif;
    font-weight: bold;
    color: #b1b1b1;
}

.presentation-shop {
    height: 300px;
    width: 350px;
    margin-right: 300px;
}

.presentation-shop h2 {
    font-size: 50px;
    
}

.separator {
    width: 150px;
    background-color: #be9359;
    height: 3px;
    margin-top: 20px;
    margin-bottom: 20px;
}

.my-color {
    color: #686868;
}

// .button {
//     display: block;
//     margin-top: 20px;
//     padding: 10px 10px;
//     text-decoration: none;
//     border: 1px solid #be9359;
//     color: #be9359;
//     width: 140px;
//     text-align: center;
// }

.image {
    height: 400px;
    width: 350px;
    position: absolute;
    top: 100px;
    right: 200px;
}

.image img {
    height: 450px;
}
</style>