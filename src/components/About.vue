<script setup>
</script>

<template>
    <div class="About">
        <div class="About-cont">
            <div class="row">
                <div class="col-md-7 col-lg-5">
                    <div class="about-content">
                        
                        <h1>About Our Clinic</h1>
                        <br />
                        <p>Since the first days of operation of Medify, our teaming has been focused on building a
                            high-qualities medicals service by clinika.
                        </p>
                        <br />
                        <button class="btn find-btn">Learn More</button>
                    </div>
                </div>
                <div class="col-md-5 col-lg-7 mt-4">
                    <img src="../assets/cover.jpg" alt="image" class="img-fluid about-img" />
                </div>
                
            </div>
        </div>
    </div>
</template>

<style>
body {
    background-color: white;
}

@font-face {
    font-family: PoppinsBold;
    src: url(../assets/Poppins-ExtraBold.ttf);
}

@font-face {
    font-family: PoppinsLight;
    src: url(../assets/Poppins-Light.ttf);
}

@font-face {
    font-family: PoppinsMedium;
    src: url(../assets/Poppins-Medium.ttf);
}


.About {
    padding: 12rem 0;
    background: #f9f9f9;
}

.About h1 {
    color: black;
    font-weight: 600;
    font-size: 2rem;
    font-family: PoppinsBold;
}

.About p{
    font-family: PoppinsLight;
    font-size: 20px;
    color: #4c4c4c;
}

.about-img {
    border-radius: 200px !important;
    max-width: 400px;
    width: 100%;
    height: 100%;
    max-height: 400px;
}

.about-content {
    padding: 4rem 2rem !important;
}

.About-cont {
    max-width: 80%;
    margin: auto;
}

</style>