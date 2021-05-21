<template>
  <div class="container d-flex flex-column header">
    <div class="d-flex flex-row justify-content-between header-top">
      <div class="header-top-left">
        <h1>
          <nuxt-link to="/" class="text-dark"> SKYWALK WAREHOUSE </nuxt-link>
        </h1>
      </div>
      <div class="header-top-right">
        <ul
          class="list-unstyled text-decoration-none d-flex flex-row justify-content-end sns-icon-list"
        >
          <li class="mr-5">
            <a href="https://www.instagram.com/gakuamano13">
              <img src="~/assets/image/instagram.jpg" alt="Instagram" />
            </a>
          </li>
          <li class="mr-5">
            <a href="https://www.facebook.com/gakuamano13">
              <img src="~/assets/image/facebook.jpg" alt="Facebook" />
            </a>
          </li>
          <li>
            <a href="https://twitter.com/gakuamano13">
              <img src="~/assets/image/twitter.jpg" alt="Twitter" />
            </a>
          </li>
        </ul>
      </div>
    </div>
    <div
      class="d-flex flex-row justify-content-between header-bottom col-xs-12"
    >
      <div class="nuxt-logo col-xs-6">
        <a href="https://nuxtjs.org/" target="_blank">
          <img src="~/assets/image/built-with-nuxt.png" alt="NUXT" />
        </a>
      </div>
      <div class="header-bottom-right col-xs-6">
        <ul
          class="list-unstyled text-decoration-none d-flex flex-row link-list"
        >
          <li class="mr-5">
            <a href="#" v-scroll-to="'#about'">ABOUT</a>
          </li>
          <li class="mr-5"><a href="#" v-scroll-to="'#work'">WORK</a></li>
          <li class="mr-5"><a href="#" v-scroll-to="'#skill'">SKILL</a></li>
          <li><a href="https://forms.gle/1pdzDv1jJdHYk3uk8" target="_blank">CONTACT</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head: {
    link: [
      {
        rel: "stylesheet",
        href:
          'https://fonts.googleapis.com/css2?family=Patrick+Hand&display=swap" rel="stylesheet',
      },
    ],
  },
};
</script>

<style lang="css" scoped>
.header {
  margin: 50px 0 30px;
}
.header-top {
  width: 100%;
}
.header-top-right {
  padding-right: 20px;
}
.nuxt-logo {
  padding-left: 3px;
}

.nuxt-logo img {
  width: 80px;
}

.header-bottom-right {
  padding-right: 20px;
}

h1 {
  font-family: "Patrick Hand", cursive;
  font-size: 40px;
}

li {
  font-family: "Patrick Hand", cursive;
}

.sns-icon-list img {
  width: 48px;
}

.header-bottom {
  margin-top: 30px;
}

.link-list a {
  color: black;
  font-size: 18px;
}

@media screen and (max-width: 560px) {
  h1 {
    font-size: 22px;
  }
  .header-top-right {
    padding-right: 0px !important;
  }
  .sns-icon-list li {
    margin-right: 10px !important;
  }
  .sns-icon-list img {
    width: 24px;
  }
  .link-list li {
    margin-right: 10px !important;
  }
  .link-list li:last-child {
    margin-right: 0px !important;
  }
  .header-bottom-right {
  padding-right: 0px !important;
}
}

@media screen and (max-width: 780px) {
  h1 {
    font-size: 26px;
  }
  .header-top-right {
    padding-right: 0px !important;
  }
  .sns-icon-list li {
    margin-right: 10px !important;
  }
  .sns-icon-list img {
    width: 36px;
  }
  .link-list li {
    margin-right: 20px !important;
  }
  .link-list a {
    font-size:12px;
  }
  .link-list li:last-child {
    margin-right: 0px !important;
  }
  .header-bottom-right {
  padding-right: 0px !important;
}
}
</style>
