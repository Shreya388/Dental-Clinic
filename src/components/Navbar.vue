<script setup>
</script>

<template>
  <!-- <div class="navbar">
    <div class="container center">
      <h1 class="navbar-brand">
       
      </h1>
      <ul class="nav-list">
        <li><a class="alink" href="/">Home</a></li>
        <li><a class="link" href="/about">About</a></li>
        <li><a class="link" href="/services">Services</a></li>
        <li><a class="link" href="/propjects">Projects</a></li>
      </ul>
      
      </div>
    </div> -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <button class="navbar-toggler border-0" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01"
        aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <a class="navbar-brand" href="#"> <img src="../assets/logo.svg" height="50px"></a>
      <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
        <ul class="navbar-nav mt-2 mt-lg-0 mx-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Projects</a>
          </li>
        </ul>
        <button class="contact-btn" href="/contact">Contact</button>
      </div>
    </div>
  </nav>
</template>

<style>
body {
  background-color: white;
}

.nav-link {
  color: #555;
  font-size: 20px;
  font-family: PoppinsMedium;
  padding-left: 20px !important;
  padding-right: 20px !important;
}


.navbar {
  background-color: rgb(255, 255, 255) !important;
  padding: 3.5vh;
  z-index: 1;
  border-bottom: 1px solid #fbfbfb;
}

.contact-btn {
  border-radius: 0px;
  padding: 10px 20px;
  background-color: #017fbb;
  color: white;
  text-decoration: none;
  font-family: PoppinsMedium;
  border-radius: 30px;
  border: 0;
  margin-left: 20px !important;
  margin-right: 20px !important
}

.contact-btn:hover {
  padding: 10px 20px;
  background-color: #017fbb;
  color: white;
  text-decoration: none;
  font-family: PoppinsMedium;
}
</style>