<template>
  <div class="text-center skill-section" id="skill">
    <h2>SKILL</h2>
    <div data-aos="zoom-out-up" data-aos-offset="200" data-aos-duration="500" class="container">
      <section id="sec">
        <ul class="d-flex justify-content-center skill-container">
          <li class="skill-list">
            <h3>HTML</h3>
            <img src="~assets/image/logo/html.png" alt="html" />
          </li>
          <li class="skill-list">
            <h3>CSS</h3>
            <img src="~assets/image/logo/css.png" alt="css" />
          </li>
          <li class="skill-list">
            <h3>Javascript</h3>
            <img src="~assets/image/logo/javascript.png" alt="javascript" />
          </li>
          <li class="skill-list">
            <h3>Vue</h3>
            <img src="~assets/image/logo/vue.png" alt="vue" />
          </li>
          <li class="skill-list">
            <h3>Nuxt</h3>
            <img
              src="~assets/image/logo/nuxt.png"
              alt="nuxt"
              class="nuxt-logo"
            />
          </li>
          <li class="skill-list">
            <h3>PHP</h3>
            <img src="~assets/image/logo/php.png" alt="php" />
          </li>
          <li class="skill-list">
            <h3>Laravel</h3>
            <img src="~assets/image/logo/laravel.png" alt="laravel" />
          </li>
          <li class="skill-list">
            <h3>MySQL</h3>
            <img src="~assets/image/logo/mysql.png" alt="laravel" />
          </li>
          <li class="skill-list">
            <h3>Github</h3>
            <img src="~assets/image/logo/github.png" alt="github" />
          </li>
          <li class="skill-list">
            <h3>Firebase</h3>
            <img src="~assets/image/logo/firebase.png" alt="firebase" />
          </li>
        </ul>
      </section>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="css"scoped>
.skill-section {
  max-width:1200px;
  margin: 50px auto 0;
}

.skill-container {
    background-color: rgba(0,201,167,.1);
  padding:50px;
}

p {
  font-family: "Patrick Hand", cursive;
  font-size: 16px;
}

h2 {
  font-family: "Patrick Hand", cursive;
  font-size: 42px;
}

h3 {
  font-family: "Patrick Hand", cursive;
  font-size: 28px;
}

#sec {
  font-family: "Raleway", sans-serif;
  padding: 50px 0;
  background: #fff;
  text-align: center;
  word-wrap: break-word;
}
#sec h2 {
  font-weight: 200;
  font-size: 30px;
  color: #63b7e6;
}
#sec ul {
  margin: 0;
  display: flex;
  flex-flow: row wrap;
  list-style: none;
}
#sec ul li {
  margin: 15px;
  padding: 15px;
  width: 200px;
  transition: box-shadow 0.3s;
}
#sec ul li:hover {
  box-shadow: 0 12px 15px 0 rgba(0, 0, 0, 0.24),
    0 17px 50px 0 rgba(0, 0, 0, 0.19);
}
#sec ul li:hover span {
  color: #63b7e6;
}
#sec ul li:hover p {
  color: #555;
}
#sec ul li:hover h3 {
  color: #63b7e6;
}
#sec ul li:hover h3:after {
  width: 25px;
}
#sec ul li span {
  font-size: 2.6em;
  display: block;
  transition: color 0.3s;
  color: #a2a2a2;
}
#sec ul li span:before,
#sec ul li span:after {
  position: static;
}
#sec ul li h3 {
  color: #6f6f6f;
  display: inline-block;
  font-size: 24px;
  font-weight: 100;
  transition: color 0.3s;
}
.nuxt-logo {
  width: 48px;
}

@media screen and (max-width: 560px) {
  #sec {
  padding: 10px 0;
}
  #sec ul {
    padding-left: 0px;
  }

  #sec h3 {
    text-align: center;
  }

  #sec ul li {
    text-align: center;
    margin: 10px;
    padding: 10px;
    width: 80px;
    transition: box-shadow 0.3s;
  }
  #sec img {
  width:42px;

}
.skill-list {
  display:flex;
  flex-direction:column;
  align-items:center;
}
}
</style>
