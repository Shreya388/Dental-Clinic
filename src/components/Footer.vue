<script>

</script>

<template>
    <div class="submit-email">
        <div class="container text-center">
            <input type="text" placeholder="Your Email" />
            <button class="send">Send</button>
        </div>
    </div>

    <div class="Footer">
        <div class="container">
            <div class="div-cont">
                <div class="col-md-12">
                    <div class="row">
                        <div class="col-md-4 text-white">
                            <div class="pl-4 pr-4">
                            <h1>+Clinic</h1>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus labore fuga
                                exercitationem praesentium! Accusantium neque quibusdam!</p>
                        </div>
                        </div>
                        <div class="col-md-2 text-white">
                        </div>
                        <div class="col-md-3">
                            <ul>
                                <p class="title">About</p>
                                <li><a href="#">Home</a></li>
                                <li><a href="#">About Us</a></li>
                                <li><a href="#">Our Team</a></li>
                                <li><a href="#">About Us</a></li>
                                <li><a href="#">Services</a></li>
                                <li><a href="#">Appointments</a></li>
                                <li><a href="#">Patient Resources</a></li>
                            </ul>
                        </div>
                        <div class="col-md-3">
                            <ul>
                                <p class="title">Support</p>
                                <li><a href="#">Contact Us</a></li>
                                <li><a href="#">FAQs</a></li>
                                <li><a href="#">Testimonials</a></li>
                                <li><a href="#">Privacy Policy</a></li>
                                <li><a href="#">Emergency Care</a></li>
                            </ul>
                        </div>

                    </div>
                </div>
            </div>
            <div class="copyright-nav text-center text-white">
                &copy; Copyright 2023
            </div>
        </div>
    </div>
</template>

<style>
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

.submit-email{
    padding: 8rem 0;
    background-color: #333333;
}

.submit-email input{
    background-color: white;
    width: 16rem;
    padding: 10px 10px;
    border-radius: 0;
    border: none;
}

.submit-email button{
    background-color: #ebebeb;
    padding: 10px 40px;
    color: #000;
    border: none;
}

.Footer {
    background: linear-gradient(180deg, #017fbb, #00324a);
}

.Footer a {
    color: rgb(228, 228, 228);
    font-family: PoppinsLight;
}

.Footer li {
    list-style-type: none;
}

.Footer ul {
    list-style-type: none;
}

.Footer h1 {
    color: white;
}

.div-cont {
    padding-top: 200px;
    padding-bottom: 200px;
}

.Footer .title {
    font-size: 22px;
    font-weight: bold;
    font-family: PoppinsBold;
    color: white;
}

.Footer .copyright-nav{
    padding-top: 15px;
    padding-bottom: 15px;
}
</style>