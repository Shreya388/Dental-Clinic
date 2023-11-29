<script setup>
</script>

<template>
    <div class="Services">
        <div class="Services-cont">
            <div class="row">
                <div class="col-md-6 col-lg-4 col-sm-3">
                    <img class="item-img" src="../assets/routine.jpg" height="10%" />
                    <div class="item">
                        <div class="item-content">
                            <h1>Routine Check-ups</h1>
                            <br />
                            <p>Regular examination maintains oral health by cleaning.</p>
                        </div>
                        <button class="btn service-btn">Learn More</button>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4 col-sm-3">
                    <img class="item-img" src="../assets/xray.jpg" height="10%" />
                    <div class="item">
                        <div class="item-content">
                            <h1>X-rays</h1>
                            <br />
                            <p>Diagnostics imaging to assess the conditon of teeth.</p>
                        </div>
                        <button class="btn service-btn">Learn More</button>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4 col-sm-3">
                    <img class="item-img" src="../assets/filling.jpg" height="10%" />
                    <div class="item">
                        <div class="item-content">
                            <h1>Fillings</h1>
                            <br />
                            <p>Fixing cavities by filling tooth with amalgam, composite resin. </p>
                        </div>
                        <button class="btn service-btn">Learn More</button>
                    </div>
                </div>
            </div>
            <br /><br />
            <div class="row mt-4">
                <div class="col-md-6 col-lg-4 col-sm-3">
                    <img class="item-img" src="../assets/extraction.jpg" height="10%" />
                    <div class="item">
                        <div class="item-content">
                            <h1>Extractions</h1>
                            <br />
                            <p>Removal of damaged or problematic teeth
                            </p>
                        </div>
                        <button class="btn service-btn">Learn More</button>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4 col-sm-3">
                    <img class="item-img" src="../assets/routine.jpg" height="10%" />
                    <div class="item">
                        <div class="item-content">
                            <h1>Root Canal Therapy</h1>
                            <br />
                            <p>Treatment for infected or damaged tooth pulp.
                            </p>
                        </div>
                        <button class="btn service-btn">Learn More</button>
                    </div>
                </div>
                <div class="col-md-6 col-lg-4 col-sm-3">
                    <img class="item-img" src="../assets/xray.jpg" height="10%" />
                    <div class="item">
                        <div class="item-content">
                            <h1>Gum Disease Treatment</h1>
                            <br />
                            <p>Services for treating and preventing gum disease.
                            </p>
                        </div>
                        <button class="btn service-btn">Learn More</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="Appointment">
        <div class="container mx-auto">
            <div class="row">
                <div class="col-md-6">
                    <div class="card border-0">
                    <img src="../assets/doctor.jpg" />
                </div>
                </div>
                <div class="col-md-6">
                    <div class="appointment-content">
                        <h1>Take the first step towards a healthy smile</h1>
                        <p>Schedule an Appointment</p>

                        <input class="name" type="text" placeholder="Patients Name" />
                        <input class="phone" type="number" placeholder="Mobile Number" /><br />
                        <input class="date" type="date" />
                        <input class="time" type="time" /><br/><br />
                        <button class="book-btn">Book Now</button>
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

*:focus {
    outline: none;
}


.name{
    border: 0;
    border-bottom: 2px solid #0087b5;
    border-radius: 0;
    padding: 10px 0;
    margin: 5px;
    width: 200px;
}

.phone{
    border: 0;
    border-bottom: 2px solid #0087b5;
    border-radius: 0;
    padding: 10px 0;
    margin: 5px;
    width: 200px;
}

.date {
    margin: 5px;
    border: 0;
    border-bottom: 2px solid #0087b5;
    padding: 10px 0;
    color: grey;
    width: 200px;
}

.time{
    margin: 5px;
    border: 0;
    border-bottom: 2px solid #0087b5;
    padding: 10px 0;
    color: grey;
    width: 200px;
}

.appointment-content{
    padding: 5rem 2rem;
    
}

.appointment-content h1{
    font-family: PoppinsBold;
}

.appointment-content p{
    font-family: PoppinsLight;
    color: purple;
}

.doctor-img {
    background-image: url(../assets/doctor.jpg);
    background-position: top;
    border-radius: 5px;
}

.Services {
    padding: 12rem 0;
}

.Services .item-content {
    height: 9.5em;
}

.Services .item {
    margin: 4rem 1.5rem;
}

.Services h1 {
    color: black;
    font-weight: 600;
    font-size: 1.5rem;
    font-family: PoppinsLight;
}

.Services p {
    font-family: PoppinsLight;
    font-size: 18px;
    color: #4c4c4c;
    word-spacing: 0.05em !important;
}

.about-img {
    border-radius: 0;
    max-width: 400px;
    width: 100%;
    height: 100%;
    max-height: 400px;
}

.about-content {
    padding: 4rem 6rem;
}

.Services-cont {
    max-width: 70%;
    margin: auto;
}

.service-btn {
    border-radius: 30px;
    padding: 10px 20px;
    background-color: transparent;
    color: #222;
    border: 1px solid #222;
    font-family: PoppinsMedium;
}

.service-btn:hover {
    border-radius: 30px;
    background-color: #222;
    color: white;
}


.book-btn {
    border-radius: 0;
    padding: 10px 20px;
    background-color: #222;
    color: white;
    border: 1px solid #222;
    font-family: PoppinsMedium;
}


.item-img {
    height: 250px;
    width: 300px;
    border-radius: 5px;
}
</style>