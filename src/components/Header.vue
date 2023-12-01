<script setup>

</script>

<template>
    <div class="Header">
        <div class="header-cont">
            <div class="row">
                <div class="col-md-5 col-lg-5 mt-4">
                    <img src="../assets/appointment.png" alt="image" class="img-fluid header-img" />
                </div>
                <div class="col-md-7 col-lg-7">
                    <div class="header-content">
                        <h1>Find a Doctor &
                            Book Appointment</h1>
                        <br />
                        <p>Since the first days of operation of Medify, our teaming has been focused on building a
                            high-qualities medicals service by clinika.
                        </p>
                        <br />
                        <button class="btn find-btn">Find A Doctor</button>
                    </div>
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


.Header {
    margin: 12rem 0;
}

.Header h1 {
    color: #3c3c3c;
    font-weight: 600;
    font-size: 3rem;
    font-family: PoppinsBold;
}

.Header p{
    font-family: PoppinsLight;
    font-size: 20px;
    color: #4c4c4c;
}

.header-img {
    max-width: 400px;
    width: 100%;
    height: 100%;
    max-height: 400px;
    border-radius: 5px;
}

.header-cont {
    max-width: 80%;
    margin: auto;
}

.find-btn {
    border-radius: 0px;
    padding: 15px 40px;
    background-color: #017fbb;
    color: white;
    border-radius: 30px;
}
</style>