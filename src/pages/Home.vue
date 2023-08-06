<template>
  <Navbar />
  <div class="main-content">
    <div class="section1 p-30" id="Home">
      <div class="sec-title">
        <div class="pg-sub-title">Home</div>
        <div class="pg-title">My Profile</div>
      </div>
      <div class="d-flex-align-center">
        <div class="user-img flex-1" style="text-align: center">
          <img src="../assets/images/me.jpg" style="max-height: 750px" />
        </div>
        <div class="user-profile flex-1">
          <div class="pro-details">
            <div class="sm-text">HELLO EVERYBODY, I AM</div>
            <div class="name">Bardia Rezaei Kalantari</div>
            <div>AKA Darmond157</div>
            <div class="role">Junior Full-Stack Developer</div>
          </div>
          <div class="text">
            You will begin to realise why this exercise is called the Dickens
            Pattern (with reference to the ghost showing Scrooge some different
            futures)
          </div>
          <div class="pr-list">
            <ul>
              <li>
                <i class="fa fa-calendar" aria-hidden="true"></i> 26th Jan, 2003
              </li>
              <li>
                <i class="fa fa-phone" aria-hidden="true"></i> +98-9903908412
              </li>
              <li>
                <i class="fa fa-envelope" aria-hidden="true"></i>
                bardiarezaeikalantari@gmail.com
              </li>
              <li>
                <i class="fa fa-map-marker" aria-hidden="true"></i> Tehran, Iran
              </li>
            </ul>
          </div>
          <div class="social-icons-head">
            <ul>
              <li>
                <a
                  href="https://www.linkedin.com/in/bardia-rezaei-kalantari-0a0921219/"
                  ><i class="fa fa-linkedin-square" aria-hidden="true"></i
                ></a>
              </li>
              <li>
                <a href=""><i class="fa fa-telegram" aria-hidden="true"></i></a>
              </li>
              <li>
                <a href="https://github.com/darmond157"
                  ><i class="fa fa-github" aria-hidden="true"></i
                ></a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";
export default {
  components: {
    Navbar,
  },
};
</script>