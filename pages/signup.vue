<template>
  <div>
    <div class="mob_nav">
      <img width="100px" src="~/assets/images/logo.png" alt="" />
    </div>

    <b-navbar
      class="navbar px-5"
      toggleable="lg"
      type="transparent"
      variant="transparent"
    >
      
      <b-navbar-brand >
        <NuxtLink to="/">
        <img width="100px" src="~/assets/images/logo.png" alt="" />
      </NuxtLink>
      </b-navbar-brand>

      <b-navbar-toggle class="text-white" target="nav-collapse"
        ><i class="fas fa-bars fs-4 text-white"></i
      ></b-navbar-toggle>

      <b-collapse id="nav-collapse" class="mx-auto" is-nav>
        <b-navbar-nav class="ms-auto mb-2 mb-lg-0">
          
          <b-nav-item class="mx-2"
            >
            <NuxtLink to="/home" class="text-white">Home
            </NuxtLink>
            </b-nav-item
          >

          
          <b-nav-item class="mx-2"
            >
            <NuxtLink to="/aboutus" class="text-white">About Us
            </NuxtLink>
            </b-nav-item
          >

          
          <b-nav-item class="mx-2">
            <NuxtLink to="/" class="text-white">Contact Us
            </NuxtLink>
            </b-nav-item>

          
          <b-nav-item class="mx-2"
            >
            <NuxtLink to="/terms" class="text-white">
              Terms & Conditions
            </NuxtLink>
            </b-nav-item
          >

          
          <b-nav-item
            class="mx-2"
            >
            <NuxtLink to="/privacypolicy" class="text-white">
              Privacy Policy
            </NuxtLink>
            </b-nav-item
          >
          
        </b-navbar-nav>
      </b-collapse>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ms-auto mb-2 mb-lg-0">
          <NuxtLink to="/">
          <button class="login me-3 mb-2">Login</button>
          </NuxtLink>
          <NuxtLink to="/signup">
          <button class="signup me-3 mb-2">Sign Up</button>
          </NuxtLink>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>

    <div class="bg">
      <div
        class="container d-flex justify-content-center flex-column align-items-center"
      style="margin-top: 100px">
        <div class="input-group mb-3">
          <input
            type="text"
            class="mt-5 form-control text-white"
            placeholder="Full Name"
            aria-label="Full Name"
            aria-describedby="basic-addon1"
          />
        </div>
        <div class="input-group mb-3">
          <input
            type="text"
            class="form-control text-white"
            placeholder="Username"
            aria-label="Username"
            aria-describedby="basic-addon1"
          />
        </div>
        <div class="input-group mb-3">
          <input
            type="email"
            class="form-control text-white"
            placeholder="Email"
            aria-label="Email"
            aria-describedby="basic-addon1"
          />
        </div>
        <div class="input-group mb-3">
          <input
            type="password"
            class="form-control text-white"
            placeholder="Pasword"
            aria-label="Pasword"
            aria-describedby="basic-addon1"
          />
        </div>
        <a href=""><p class="text-white fw-bold fs-6">Forgot Password?</p></a>
        <button class="login2">
          Sign Up <i class="fas fa-arrow-right text-white"></i>
        </button>
        <a href="https://writeout.netlify.app/">
          <button class="signup2 mt-3">
            Login <i class="fas fa-arrow-right text-white"></i>
          </button>
        </a>
      </div>

      <img class="poly1" src="~/assets/images/polygon1.svg" alt="">
      <img class="poly2" src="~/assets/images/polygon2.svg" alt="">
      <img class="poly3" src="~/assets/images/polygon3.svg" alt="">
      <img class="poly4" src="~/assets/images/polygon4.svg" alt="">
    </div>
  </div>
</template>
