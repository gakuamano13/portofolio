<template>
  <div class="main_content" id="about">
    <div class="text-center about">
      <div><h3>ABOUT</h3></div>
    </div>
    <div
      class="container d-flex flex-row justify-content-center about-wrapper"
    >

      <div
        class="card card-container"
        data-aos="fade-right"
        data-aos-offset="300"
        data-aos-duration="1000"
      >
        <kinesis-container class="kinesis">
          <kinesis-element :strength="30" type="depth">
            <div class="photo"></div>
          </kinesis-element>
        </kinesis-container>
        <div class="banner"></div>
        <ul>
          <li class="profile-name">Gaku Amano</li>
          <li class="my-2">Junior Web Developer</li>
          <li class="mt-3">Social Links:</li>
        </ul>
        <div
          class="social-media-banner d-flex flex-row justify-content-center sns-icon-list"
        >
          <a href="https://www.instagram.com/gakuamano13/" class="mx-2">
            <img src="~/assets/image/about/icons8-instagram-old-50.png" alt="Instagram" />
          </a>
          <a href="https://www.facebook.com/gakuamano13" class="mx-2">
            <img src="~/assets/image/about/icons8-facebook-50.png" alt="Facebook" />
          </a>
          <a href="https://twitter.com/gakuamano13" class="mx-2">
            <img src="~/assets/image/about/icons8-twitter-circled-50.png" alt="Twitter" />
          </a>
          <a href="https://github.com/gakuamano13" class="mx-2">
            <img src="~/assets/image/about/icons8-github-50.png" alt="Github" />
          </a>
        </div>
      </div>

      <div
        class="text-center self-introduction"
        data-aos="fade-left"
        data-aos-offset="300"
        data-aos-duration="1000"
      >
        <p>Hi, there!</p>

          <p class="w-100">I'm <span class="name">Gaku Amano.</span></p>

        <p>I am a junior web developer living in the Far East: Japan.</p>
        <p>What I LOVE to do :</p>
        <p>both FRONT-END & BACK-END.</p>
        <p>Since I fell in love with web development a year ago,</p>
        <p>I have been making fairly good progress.</p>
        <p>Here are some things I've done.</p>

        <!-- <a href="" class="d-flex flex-row">
          <font-awesome-icon :icon="['fab', 'twitter']" />
        </a>
        <a href="" class="d-flex flex-row">
          <font-awesome-icon :icon="['fab', 'instagram']" />
        </a>
        <a href="" class="d-flex flex-row">
          <font-awesome-icon :icon="['fab', 'github']" />
        </a> -->
        <div class="arrow">
          <a href="#" class="arrow"
            ><img
              src="~/assets/image/works/down-arrow.png"
              alt=""
              v-scroll-to="'#work'"
          /></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style lang="css" scoped>

.main_content {
  margin: 100px auto 80px;
}

.self-introduction {
  padding-top: 0px;
}

.about {
  margin: 100px 0;
}

.about-wrapper {
  background-color: rgba(0,201,167,.1);
  padding:50px;
}

li {
  font-family: "Patrick Hand", cursive;
}

p {
  font-family: "Patrick Hand", cursive;
  font-size: 24px;
}
.name {
  font-size: 48px;
}
.profile-name {
  font-size: 48px;
  margin-top: -30px;
}

h3 {
  font-family: "Patrick Hand", cursive;
  font-size: 42px;
}

.card {
  z-index: 1;
  position: relative;
  width: 400px;
  height: 500px;
  background-color: white;
  -webkit-box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
  -moz-box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
  /* -webkit-transition: all 0.7s ease-in-out;
  -moz-transition: all 0.7s ease-in-out;
  -o-transition: all 0.7s ease-in-out;
  -ms-transition: all 0.7s ease-in-out; */
}

.card-container {
  margin-right: 80px;
}

.banner {
  z-index: 2;
  position: relative;
  margin-top: -140px;
  width: 100%;
  height: 150px;
  background-image: url("~assets/image/works/ocean.jpg");
  background-size: cover;
  background-position: 50%;
  border-bottom: solid 1px lightgrey;

  /* -webkit-transition: all 0.7s ease-in-out;
  -moz-transition: all 0.7s ease-in-out;
  -o-transition: all 0.7s ease-in-out;
  -ms-transition: all 0.7s ease-in-out; */
}

.kinesis {
  z-index: 5;
}

.photo {
  z-index: 3;
  position: relative;
  border-radius: 50%;
  height: 140px;
  width: 140px;
  background-color: white;
  margin: 0 auto;
  background-image: url("~assets/image/works/portrait.jpg");
  background-size: cover;
  background-position: 50%;
  top: 80px;
  -webkit-box-shadow: inset 0px 0px 5px 1px rgba(0, 0, 0, 0.3);
  -moz-box-shadow: inset 0px 0px 5px 1px rgba(0, 0, 0, 0.3);
  box-shadow: inset 0px 0px 5px 1px rgba(0, 0, 0, 0.3);
  /* -webkit-transition: top 0.7s ease-in-out, background 0.15s ease;
  -moz-transition: top 0.7s ease-in-out, background 0.15s ease;
  -o-transition: top 0.7s ease-in-out, background 0.15s ease;
  -ms-transition: top 0.7s ease-in-out, background 0.15s ease; */
}

.card ul {
  list-style: none;
  text-align: center;
  padding-left: 0;
  margin-top: 100px;
  margin-bottom: 30px;
  font-size: 20px;
  /* -webkit-transition: all 0.7s ease-in-out;
  -moz-transition: all 0.7s ease-in-out;
  -o-transition: all 0.7s ease-in-out;
  -ms-transition: all 0.7s ease-in-out; */
}

.card ul.active {
  opacity: 0;
  visibility: hidden;
}

.social-media-banner {
  width: 100%;
  height: 50px;
  /* -webkit-transition: all 1.5s ease-in-out;
  -moz-transition: all 1.5s ease-in-out;
  -o-transition: all 1.5s ease-in-out;
  -ms-transition: all 1.5 ease-in-out; */
}

.social-media-banner.active {
  opacity: 0;
  visibility: hidden;
  /* -webkit-transition: all 0.1s ease-in-out;
  -moz-transition: all 0.1s ease-in-out;
  -o-transition: all 0.1s ease-in-out;
  -ms-transition: all 0.1s ease-in-out; */
}

.sns-icon-list img {
  width: 48px;
}
.arrow {
  margin-top: 40px;
}

@media screen and (max-width: 780px) {
  .main_content {
    margin-top: 10px;
    margin-bottom: 80px;
  }
  .card {
    z-index: 1;
    position: relative;
    width: 250px;
    height: 500px;
    margin-right:20px;
  }
  .self-introduction {
    width: 250px;
    height: 500px;
    margin-left:20px;
  }
  .card-container {
    margin-right: 0px !important;
  }
  p {
    font-size: 18px;
  }
  .name {
    font-size: 32px;
  }
}

@media screen and (max-width: 560px) {
  .main-content {
  padding:0px;
  }
  .about {
    margin: 50px auto;
  }
  .about-wrapper {
    flex-direction: column !important;
    align-items: center;
  }
  .card {
    width: 300px;
    height: 420px;
  }
  .photo {
  z-index: 3;
  position: relative;
  border-radius: 50%;
  height: 120px;
  width: 120px;
  background-size: cover;
  background-position: 50%;
  top: 60px;
}
  .card-container {
    margin-right: 0px !important;
  }
  .self-introduction {
    margin-top: 30px;
    height:600px;
    margin-left:0px;
  }
  .self-introduction p {
    font-size: 16px;
  }
  .main_content {
    margin-top: 0px;
    margin-bottom: 20px;
  }
  .profile-name {
  font-size: 36px;
  margin-top: -50px;
}
.arrow {
  margin-top: 40px !important;
}
}
</style>






