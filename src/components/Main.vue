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
        
        <div class="services"></div>
    </main>
</template>

<script>
export default {
    name: 'Main',
};
</script>

<style lang="scss" scoped>
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
}

.pro {
    font-size: 40px;
    margin-top: 15px;
}

.separator {
    margin-top: 1px;
    width: 100%;
}


</style>