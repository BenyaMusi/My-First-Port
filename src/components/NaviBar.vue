<template>
  <div class="navigation" :class="{ 'navbar--hidden': !showNavbar }">
    <div class="row navi">
      <div>
        <div @click="page((index = 1))" class="name">Butter<span>Ben</span></div>
      </div>
      <ul class="item-center">
        <li><div @click="page((index = 4))">Activities</div></li>
        <li><div @click="page((index = 3))">Works</div></li>
        <!-- <li><router-link :to="'/skills'">Skills</router-link></li> -->
        <li><div @click="page((index = 2))">About Me</div></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {
      showNavbar: true,
      lastScrollPosition: 0,
    };
  },
  methods: {
    scrollListener() {
      const currentScrollPosition =
        window.pageYOffset || document.documentElement.scrollTop;
      this.showNavbar = currentScrollPosition < this.lastScrollPosition;
      this.lastScrollPosition = currentScrollPosition;
    },
  },
  page(index) {
    var nav = document.getElementsByClassName("navi")[index];
    document
      .getElementsByClassName("page")
      [index].scrollIntoView({ behavior: "smooth", block: "center" });
    nav.classList.add("navi_active");
  },
  mounted() {
    window.addEventListener("scroll", this.scrollListener);
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Kaushan+Script&family=Satisfy&family=Square+Peg&display=swap");
.navbar--hidden {
  transform: translate3d(0, -100%, 0);
}
.navigation {
  position: fixed;
  width: 100%;
  height: var(--navigation-height);
  top: 0px;
  transition: transform 0.2s;
  color: #000;
  background: #fff;
}
.navi {
  display: grid;
  grid-template-columns: 1fr 2fr;
  margin: 0px 5%;
  position: relative;
  top: 50%;
  transform: translateY(-50%);
}
ul {
  padding: 0px;
  position: relative;
  top: 50%;
  transform: translateY(-50%);
}
.navi li {
  display: inline;
  margin-left: 10%;
  float: right;
  font-size: 20px;
  cursor: pointer;
}
.navi a {
  text-decoration-line: none;
  color: #fff;
}
.navigation .name {
  font-family: "Kaushan Script", cursive;
  font-family: "Satisfy", cursive;
  font-family: "Square Peg", cursive;
  font-size: 60px;
  cursor: pointer;
}
span {
  color: #9f7beb;
}
.navigation .name:hover {
  color: #9f7beb;
}
</style>
