<template>
  <div>
    <div class="mob_nav justify-content-center">
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

    <div class="bg2 pt-5">
      <div class="mx-3 mx-lg-5 mx-md-5" style="margin-top: 110px">
        <p class="pb-4 pb-lg-5 fs-5 w-100 text-center">Privacy Policy</p>
        <p class="fw-bold">We are committed to protecting your privacy</p>
        <p>
          We collect the minimum amount of information about you that is
          commensurate with providing you with a satisfactory service. This
          policy indicates the type of processes that may result in data being
          collected about you. Your use of this website gives us the right to
          collect that information.
        </p>
        <p></p>
        <p>Information Collected</p>
        <p>
          We may collect any or all of the information that you give us
          depending on the type of transaction you enter into, including your
          name, address, telephone number, and email address, together with data
          about your use of the website. Other information that may be needed
          from time to time to process a request may also be collected as
          indicated on the website.
        </p>
        <p></p>
        <p class="fw-bold">Information Use</p>
        <p>
          We use the information collected primarily to process the task for
          which you visited the website. Data collected in the UK is held in
          accordance with the Data Protection Act. All reasonable precautions
          are taken to prevent unauthorised access to this information. This
          safeguard may require you to provide additional forms of identity
          should you wish to obtain information about your account details.
        </p>
        <p class="fw-bold">Cookies</p>
        <p>
          Your Internet browser has the in-built facility for storing small
          files - "cookies" - that hold information which allows a website to
          recognise your account. Our website takes advantage of this facility
          to enhance your experience. You have the ability to prevent your
          computer from accepting cookies but, if you do, certain functionality
          on the website may be impaired.
        </p>
        <p class="fw-bold">Disclosing Information</p>
        <p>
          We do not disclose any personal information obtained about you from
          this website to third parties unless you permit us to do so by ticking
          the relevant boxes in registration or competition forms. We may also
          use the information to keep in contact with you and inform you of
          developments associated with us. You will be given the opportunity to
          remove yourself from any mailing list or similar device. If at any
          time in the future we should wish to disclose information collected on
          this website to any third party, it would only be with your knowledge
          and consent.
        </p>
        <p>
          We may from time to time provide information of a general nature to
          third parties - for example, the number of individuals visiting our
          website or completing a registration form, but we will not use any
          information that could identify those individuals.
        </p>
        <p>
          In addition Dummy may work with third parties for the purpose of
          delivering targeted behavioural advertising to the Dummy website.
          Through the use of cookies, anonymous information about your use of
          our websites and other websites will be used to provide more relevant
          adverts about goods and services of interest to you. For more
          information on online behavioural advertising and about how to turn
          this feature off, please visit youronlinechoices.com/opt-out.
        </p>
        <p class="fw-bold">Changes to this Policy</p>
        <p>
          Any changes to our Privacy Policy will be placed here and will
          supersede this version of our policy. We will take reasonable steps to
          draw your attention to any changes in our policy. However, to be on
          the safe side, we suggest that you read this document each time you
          use the website to ensure that it still meets with your approval.
        </p>
        <p class="fw-bold">Contacting Us</p>
        <p>
          If you have any questions about our Privacy Policy, or if you want to
          know what information we have collected about you, please email us at
          paul@dummymag.com. You can also correct any factual errors in that
          information or require us to remove your details form any list under
          our control.
        </p>
      </div>

      <img class="outer_poly1" src="~/assets/images/outer_polygon1.svg" alt="" />
      <img class="outer_poly2" src="~/assets/images/outer_polygon2.svg" alt="" />
      <img class="outer_poly3" src="~/assets/images/outer_polygon3.svg" alt="" />
      <img class="outer_poly4" src="~/assets/images/outer_polygon4.svg" alt="" />

      <img class="mob_poly1" src="~/assets/images/mob_Polygon1.svg" alt="" />
      <img class="mob_poly2" src="~/assets/images/mob_polygon2.svg" alt="" />
      <img class="mob_poly3" src="~/assets/images/mob_polygon3.svg" alt="" />
      <img class="mob_poly4" src="~/assets/images/mob_polygon4.svg" alt="" />
    </div>
  </div>
</template>
