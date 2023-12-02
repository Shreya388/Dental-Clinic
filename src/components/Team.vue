<script setup>
</script>

<template>
    <div class="Team">
        <div class="Team-cont text-center">
            <h1 class="heading">Our Awesome Team</h1>
            <p>They are individuals who have entrusted us with their health and well-being
            </p>
            <br /><br />

            <div class="row">
                <div class="col-md-6 col-lg-3 col-sm-12">
                    <img class="item-img" src="../assets/doctorOne.jpg" height="10%" />
                    <div class="team-des">
                        <div class="Team-content">
                            <h4>Anna Lopez</h4>
                            <p>Health Information Technician</p>
                        </div>
                        
                    </div>
                </div>
                <div class="col-md-6 col-lg-3 col-sm-12">
                    <img class="item-img" src="../assets/doctorTwo.jpg" height="10%" />
                    <div class="item">
                        <div class="Team-content">
                            <h4>Kate Jones</h4>
                            <p>Medical Transcriptionist</p>
                        </div>
                        
                    </div>
                </div>
                <div class="col-md-6 col-lg-3 col-sm-12">
                    <img class="item-img" src="../assets/doctorThree.jpg" height="10%" />
                    <div class="item">
                        <div class="Team-content">
                            <h4>Adam Johnson</h4>
                            <p>Pharmacy Technician </p>
                        </div>
                       
                    </div>
                </div>
                <div class="col-md-6 col-lg-3 col-sm-12">
                    <img class="item-img" src="../assets/doctorThree.jpg" height="10%" />
                    <div class="item">
                        <div class="Team-content">
                            <h4>Adam Johnson</h4>
                            <p>Pharmacy Technician </p>
                        </div>
                       
                    </div>
                </div>
            </div>
            <br /><br />
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

.Team .heading{
    font-size: 3rem;
    font-family: PoppinsMedium;
}

.Team {
    padding: 12rem 0;
}

.Team p{
    font-family: PoppinsMedium;
    color: grey;
}

.Team-content{
    padding: 2rem;
    text-align: left;
}

.Team-cont {
    max-width: 80%;
    margin: auto;
}

.item-img {
    height: 300px;
    width: 300px;
    border-radius: 0;
}
</style>