<template>
  <div class="d-flex flex-row justify-content-between footer">
    <div class="footer-left">
      <ul class="list-unstyled text-decoration-none d-flex flex-row link-list">
        <li class="mr-5"><a href="#">ABOUT</a></li>
        <li class="mr-5"><a href="#">WORK</a></li>
        <li class="mr-5"><a href="#">SKILL</a></li>
        <li><a href="#">CONTACT</a></li>
      </ul>
    </div>
    <div class="footer-right">
      <small class="copyright">
        © 2021 Copyright : SKYWALK WAREHOUSE All rights reserved.
      </small>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="css" scoped>
.footer {
  max-width: 1000px;
  margin: 0 auto;
  padding: 50px;
}
.link-list a {
  color: grey;
  font-size: 12px;
  font-family: "Patrick Hand", cursive;
}

.copyright {
  font-family: "Patrick Hand", cursive;
  font-size: 16px;
}

@media screen and (max-width: 560px) {
  .copyright {
    font-family: "Patrick Hand", cursive;
    font-size: 12px !important;
  }
}

@media screen and (max-width: 780px) {
  .link-list li {
    margin-right: 15px !important;
  }
  .footer {
    flex-direction: column !important;
    align-items: center;
    padding-top: 0px;
  }
  .footer-right {
    margin-top:30px;
  }
}
</style>
