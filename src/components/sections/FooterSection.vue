<template>
  <div class="footer-section">
    <div class="container p-5">
      <h1 class="footer-badge text-center">Help empower the youth of Africa</h1>
      <div class="footer-btn mt-5 text-center">
        <button type="button" class="btn-1 mx-5">Receive news</button>
        <button type="button" class="btn">To Donate</button>
      </div>
      <div class="row mt-5">
        <div class="col">
          <h1 class="footer-title text-start">Navigation</h1>
          <p class="text-start">Home</p>
          <p class="text-start">About US</p>
          <p class="text-start">What We Do</p>
          <p class="text-start">To Donate</p>
        </div>
        <div class="col">
          <h1 class="footer-title text-start">Navigation</h1>
          <p class="text-start">Encouraging Testing</p>
          <p class="text-start">Strengthening Advocacy</p>
          <p class="text-start">Sharing Information</p>
          <p class="text-start">Building Leadership</p>
          <p class="text-start">Engaging With Global Fund</p>
          <p class="text-start">Shining a Light</p>
        </div>
        <div class="col">
          <h1 class="footer-title text-start">Legal</h1>
          <p class="text-start">General Info</p>
          <p class="text-start">Privacy Policy</p>
          <p class="text-start">Terms of Service</p>
        </div>
        <div class="col">
          <h1 class="footer-title text-start">Speak with us</h1>
          <p class="text-start">
            <a href="mailto:candleoflightfoundation@proton.me"
              >candleoflightfoundation@proton.me</a
            >
          </p>
          <p class="text-start">054 259 0653</p>
          <p class="text-start">Contact Us</p>
          <p class="text-start">
            <a href="https://www.facebook.com" target="_blank">Facebook</a>
          </p>
          <p class="text-start">
            <a href="https://www.twitter.com" target="_blank">Twitter</a>
          </p>
          <p class="text-start">
            <a href="https://www.instagram.com" target="_blank">Instagram</a>
          </p>
        </div>
      </div>
      <hr class="mt-5" />
      <div class="row mt-5">
        <div class="col-3 d-flex align-items-center">
          <div class="navbar-brand justify-content-center">
            <img class="img-fluid" src="@/assets/logo.png" alt="" />
          </div>
        </div>
        <div class="col-6 d-flex align-items-center">
          <h3 class="footer-text">
            &copy; 2023 CandleLightFoundation. All rights reserved.
          </h3>
        </div>
        <div class="col-3 d-flex align-items-center">
          <img class="img-fluid" src="@/assets/Social.svg" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterSection",
};
</script>

<style scoped>
.footer-section {
  background-color: #f4f3f3;
}

.footer-badge {
  color: #0a142f;
  text-align: center;
  font-family: Open Sans;
  font-size: 35px;
  font-style: normal;
  font-weight: 700;
  line-height: 50px;
}

.btn {
  border-radius: 5px;
  padding: 14px 32px;
  background: #e4580f;
  color: white;
  font-family: "Bebas Neue", sans-serif;
  font-size: 24px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  text-transform: capitalize;
}

.btn-1 {
  border-radius: 0px;
  padding: 14px 32px;
  background-color: transparent;
  border-radius: 5px;
  border: 1px solid #0a142f;
  color: #0a142f;
  font-family: "Bebas Neue", sans-serif;
  font-size: 24px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  text-transform: capitalize;
}

.footer-title {
  color: #0a142f;
  font-family: Open Sans;
  font-size: 15px;
  font-style: normal;
  font-weight: 700;
  line-height: normal;
  text-transform: uppercase;
}
p {
  color: #0a142f;
  font-family: Open Sans;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: 30px;
  list-style: none;
  text-align: start;
}

p a {
  text-decoration: none;
  color: #0a142f;
}

.footer-text {
  color: #0a142f;
  text-align: center;
  font-family: Open Sans;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 14px;
}
</style>
