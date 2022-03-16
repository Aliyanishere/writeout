<template>
  <div>
    <nav class="navbar navbar-expand-lg" style="background-color: transparent">
      <div class="container-fluid bg-transparent">
        <a class="navbar-brand" href="#"
          ><img width="100px" src="~/assets/images/logo.png" alt=""
        /></a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon text-white"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mx-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a
                class="nav-link active mx-2 text-white"
                aria-current="page"
                href="#"
                >Home</a
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link mx-2 text-white"
                href="http://localhost:3000/aboutus"
                >About Us</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link mx-2 text-white" href="#">Contact Us</a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link mx-2 text-white"
                href="http://localhost:3000/terms"
                >Terms & Conditions</a
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link mx-2 text-white"
                href="http://localhost:3000/privacypolicy"
                >Privacy Policy</a
              >
            </li>
            <!-- <li class="nav-item">
              <a class="nav-link mx-2 text-white" href="#">About Us</a>
            </li> -->
          </ul>
          <ul class="navbar-nav mb-2 mb-lg-0">
            <li class="nav-item">
              <a href="http://localhost:3000/"
                ><button class="login me-3">Login</button></a
              >
            </li>
            <li class="nav-item">
              <a href="http://localhost:3000/signup"
                ><button class="signup me-3">Sign Up</button></a
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>