<template>
    <footer>
        <div class="box">
            <img class="f-image" src="../assets/images/avadabarbers_footer_shop_image.png" alt="#">
            <div class="width">
                <a class="f-button" href="#">SHOP OUR RANGE NOW</a>
            </div>
        </div>
        <div class="box">
            <img class="f-logo" src="../assets/images/avadabarbers-logo-x1.png" alt="#">
            <p class="p-footer">Avada Barbers
                123 New York Street
                New York City
                info@yourwebsite.com +1 (555) 555-1212
            </p>
            <p class="s-footer">FOLLOW US</p>
            <div class="icons">
                <i class="fab fa-facebook-f"></i>
                <i class="fab fa-twitter"></i>
                <i class="fab fa-youtube"></i>
                <i class="fab fa-instagram"></i>
            </div>
        </div>
        <div class="box">
            <img class="f-image" src="../assets/images/avadabarbers_footer_appointment_image.png" alt="#">
            <div class="width">
                <a class="f-button" href="#">BOOK YOUR APPOINTMENT</a>
            </div>
        </div>
    </footer>
</template>


<script>
export default {
    name: 'Footer',
};
</script>

<style lang="scss" scoped>
footer {
    height: 500px;
    background-color: #121314;
    width: 100%;
    display: flex;
    justify-content: center;
}

.box {
    height: 300px;
    width: 200px;
    margin: 40px 20px;
}

.f-image {
    height: 200px;
    width: 100%;
}

.width {
    width: 100%;
    display: flex;
    justify-content: center;
}

.f-button {
    font-size: 13px;
    border: 1px solid #be9359;
    color: #be9359;
    padding: 13px 10px;
    text-decoration: none;
    align-self: center;
}

.f-logo {
    height: 50px;
    width: 100%;
    margin-bottom: 20px;
}

.p-footer {
    color: #b1b1b1;
    font-size: 12px;
    margin-top: 20px;
    text-align: center;
}

.s-footer {
    color: #be9359;
    text-align: center;
    margin-top: 60px;
}

.icons {
    width: 100%;
    display: flex;
    justify-content: center;
}

.icons i {
    margin-left: 10px;
    color: #bebdbd;
}


.copyright {
    height: 100px;
    width: 100%;
    background-color: #161718;
}

</style>