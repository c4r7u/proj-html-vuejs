<template>
    <main>
        <div>
            <div class="pro-barbers">
                <span class="award">AWARD WINNING</span>
                <h3 class="pro">Pro Barbers</h3>
                <a class="button" href="#">MEET YOUR NEW BARBER</a>

                <svg class="separator" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
                    <path fill="white" fill-opacity="1" d="M0,236L720,96L1540,256L1440,320L720,720L0,320Z"></path>
                </svg>
            </div>
        </div>
        
        <div class="services">
            <div class="head-services">
                <span class="award">MENS GROOMING</span>
                <h4 class="pro">Services</h4>
            </div>
            <div class="info-services">
                <div class="box">
                    <div class="margin">
                        <img class="services-img" src="../assets/images/avadabarbers-trimcut-icon-before.png" alt="#">
                    </div>
                    <h6 class="info-title">Trim & Cut </h6>
                    <span class="services-description">Avada Barbers are experts in the lickety split trim and hair cut. Quick but careful and ridiculously good looking.</span>
                </div>
                <div class="box">
                    <div class="margin">
                        <img class="services-img" src="../assets/images/avadabarbers-washndry-icon.png" alt="#">
                    </div>
                    <h6 class="info-title">Wash & Dry</h6>
                    <span class="services-description">Take a seat in our fine leather chairs, lean back and let us lather you a fresh head in a luxurious fashion.</span>
                </div>
                <div class="box">
                    <div class="margin">
                        <img class="services-img" src="../assets/images/avadabarbers-beardtrim-icon.png" alt="#">
                    </div>
                    <h6 class="info-title">Beard Tidy</h6>
                    <span class="services-description">Tame the tangles and untidy facial hairs like a gentleman with our Beard Tidy services from Avada Barbers.</span>
                </div>
            </div>
            <div class="width">
                <a class="services-button" href="#">READ ABOUT OUR SERVICES</a>
            </div>
        </div>

        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#111213" fill-opacity="1" d="M0,224L720,96L1440,224L1440,320L720,320L0,320Z"></path></svg>
    </main>
</template>

<script>
export default {
    name: 'MainServices',
};
</script>

<style lang="scss" scoped>
@import '../styles/general.scss';




.pro-barbers {
    height: 380px;
    width: 100%;
    background-image: url(../assets/images/avadabarbers-about-introbackground.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    color: white;
    text-align: center;
    padding: 30px;
}


.button {
    font-size: 13px;
    display: inline-block;
    margin-top: 20px;
    padding: 13px 10px;
    text-decoration: none;
    border: 1px solid #be9359;
    color: #be9359;
    width: 230px;
    text-align: center;
}

.award {
    margin-top: 40px;
    color: #be9359;
}

.pro {
    font-size: 40px;
    margin-top: 15px;
    color: #b1b1b1;
}

.separator {
    margin-top: 1px;
    width: 100%;
}

.services {
    width: 100%;
}

.head-services {
    text-align: center;
    width: 100%;
}

.info-services {
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

.margin {
    margin-bottom: 100px;
}


.services-img {
    height: 100px;
    position: relative;
    top: 40px;
    left: 120px;
} 

.info-title {
    color: #be9359;
    font-size: 25px;
    align-self: center;
    width: 100%;
    text-align: center;
    display: block;
}

.services-description {
    color: #b1b1b1;
    align-self: flex-end;
    width: 100%;
    text-align: center;
    display: block;
    margin-top: 40px;
}

.width {
    width: 100%;
    display: flex;
    justify-content: center;
}

.services-button {
    font-size: 13px;
    display: inline-block;
    margin-top: 20px;
    padding: 13px 10px;
    text-decoration: none;
    border: 1px solid #be9359;
    color: #be9359;
    width: 230px;
    text-align: center;
}


</style>