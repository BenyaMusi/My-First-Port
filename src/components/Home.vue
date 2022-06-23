<template>
  <div class="home">
    <div class="navigation" :class="{ 'navbar--hidden': !showNavbar }">
      <div class="row navi">
        <div>
          <a href="#first_page" class="name">Butter<span>Ben</span></a>
        </div>
        <ul class="item-center">
          <li><a href="#hobbies">Hobbies</a></li>
          <li><a href="#activities">Activities</a></li>
          <li><a href="#works">Works</a></li>
          <li><a href="#profile">About Me</a></li>
        </ul>
      </div>
    </div>
    <section class="page first_page" id="first_page">
      <div>
        <dip class="text">
          <h1>Hi! I'm <span>Noey</span></h1>
          <h1>BENYAPHA &nbsp; MUSIKARAYAKUN</h1>
          <h2>Front-end Developer</h2>
          <a
            href="https://facebook.com/benyapha.musikarayakun?_rdc=1&_rdr"
            target="_blank"
          >
            <img src="../assets/fb2.png" />
          </a>
          <a href="https://twitter.com/ButterBen2" target="_blank">
            <img src="../assets/tw2.png" />
          </a>
          <a href="https://www.instagram.com/butter_benyapha/" target="_blank">
            <img src="../assets/ig2.png" />
          </a>
        </dip>
        <img class="first_pic" src="../img/1640430303829.jpg" />
      </div>
    </section>
    <section class="page profile" id="profile">
      <div>
        <img class="second_pic" src="../img/profile.png" />
        <h1><span>ABOUT ME</span></h1>
        <div class="text">
          <!-- <div>
          <div><span>Name : </span> Benyapha Musikarayakun</div>
          <div><span>Nickname : </span> Noey / Butter / Ben</div>
          <div><span>Date of Birth : </span> 10 February 2000</div>
        </div> -->
          <p>
            &emsp;&emsp;I graduated from KMITL, faculty of Science and department of Computer Science. I've a 3.30 GPA.<br />
            With experience Front-end Developer of Co-operative Education at Finn Solution.Co.,Ltd. for 7 months.<br />
            I used Vue.js and Quasar framework for the project that I've done.<br />
            <br />
            I've studied Java in class and game developed by Monogame with c# language.
            <br />I've also had UX/UI and Design Pattern lesson. I'm willing to learn new
            things as well.
          </p>
        </div>
      </div>
    </section>
    <section class="page works" id="works">
      <h1>
        <span><center>WORKS</center></span>
      </h1>
      <h2>Co-operative Education Work</h2>
      <div>
        <p>
          FINNFAN: celebrities's time auction web application. The main fuctions that I've
          done are
        </p>
        <div class="work">
          <p>Log in / Log out & Sign up</p>
          <img class="work_pic" src="../img/cowork3.png" />
          <p>Landing Page & Table of Contents</p>
          <img class="work_pic" src="../img/cowork1.png" />
          <img class="work_pic" src="../img/cowork2.png" />
          <p>Bidding Page & Time</p>
          <img class="work_pic" src="../img/cowork4.png" />
          <p>History & Changing Profile</p>
          <img class="work_pic" src="../img/cowork5.png" />
        </div>
      </div>
      <h2>Class Works</h2>
      <div>
        <p>COMPUTER GAME PROGRAMMING : Midterm Exam</p>
        <div class="work">
          <p>Bubble shooting game</p>
          <img class="work_pic2" src="../img/work1.png" />
        </div>
      </div>
      <div>
        <p>COMPUTER GAME PROGRAMMING : Final Exam</p>
        <div class="work">
          <p>Catapult game</p>
          <img class="work_pic_small" src="../img/work3.png" />
        </div>
      </div>
      <div>
        <p>Designing Interactive System : UX / UI Project</p>
        <div class="work">
          <p>Planner mobile application</p>
          <img class="work_pic_big" src="../img/work7.png" />
          <img class="work_pic_big" src="../img/work6.png" />
        </div>
      </div>
    </section>
    <section class="page activities" id="activities">
      <h1>
        <span><center>ACTIVITIES</center></span>
      </h1>
      <h2>University's Activities</h2>
      <div>
        <p>CS CAMP 11th</p>
        <div class="act">
          <p>I was An academic staff</p>
          <img class="act_pic" src="../img/act1.png" />
          <img class="act_pic" src="../img/act2.png" />
          <img class="act_pic" src="../img/act3.png" />
          <img class="act_pic" src="../img/act5.png" />
          <img class="act_pic" src="../img/act4.png" />
        </div>
      </div>
      <div>
        <p>Sports</p>
        <div class="act">
          <p>
            In 2018, I was a member of the Faculty of Science<br />women basketball team
            to play on KMITL freshy basketball match.<br />In the same year untill 2019, I
            also played on the Com-Sci women basketball team<br />for the Vidya-Vidya
            match. Vidya-Vidya is the sport days of Faculty of Science
          </p>
          <img class="work_pic" src="../img/act6.png" />
          <p>In 2019, I ran a race in Vidya-Vidya sport days.</p>
          <img class="work_pic" src="../img/act7.png" />
          <p>In 2020, I was a member in KMITL Karate-do club</p>
          <img class="work_pic" src="../img/act8.png" />
        </div>
      </div>
      <div>
        <p>Certificate</p>
        <div class="act">
          <p>Depa & KMITL Basic product design by AR VR MR and 3D training</p>
          <img class="work_pic" src="../img/cer.png" />
        </div>
      </div>
    </section>
    <section class="page hobbies" id="hobbies">
      <h1>
        <span><center>Hobbies</center></span>
      </h1>
      <div class="hob">
        <p>
          I like drawing, it's my hobby and my part-time job.<br />
          I open low cost art commission for practise my drawing skill. These are some of
          my art works.
        </p>
        <div class="img_draw">
          <img class="draw" src="../img/21.png" />
          <img class="draw" src="../img/10.png" />
          <img class="draw" src="../img/08.png" />
          <img class="draw" src="../img/09.png" />
          <img class="draw" src="../img/05.png" />
          <img class="draw" src="../img/06.png" />
          <img class="draw" src="../img/11.png" />
          <img class="draw" src="../img/13.png" />
          <img class="draw" src="../img/14.png" />
          <img class="draw" src="../img/04.png" />
          <img class="draw" src="../img/03.png" />
          <img class="draw" src="../img/01.png" />
          <img class="draw" src="../img/02.png" />
          <img class="draw" src="../img/12.png" />
          <img class="draw" src="../img/18.png" />
          <img class="draw" src="../img/23.png" />
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "HomePage",
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
  firstPage() {
    document
      .getElementsByClassName("first_page")[0]
      .scrollIntoView({ behavior: "smooth", block: "center" });
  },
  profile() {
    document
      .getElementsByClassName("profile")[0]
      .scrollIntoView({ behavior: "smooth", block: "center" });
  },
  works() {
    document
      .getElementsByClassName("works")[0]
      .scrollIntoView({ behavior: "smooth", block: "center" });
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
  z-index: 1;
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
  color: #000;
}
.navi a {
  text-decoration-line: none;
  color: #000;
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
.page {
  margin: 0% 5%;
  padding-top: 70px;
}
.first_page {
  text-align: center;
  height: 100vh;
}
.first_pic {
  z-index: -5;
  height: 100vh;
  filter: grayscale(100%) brightness(75%) sepia(80%) hue-rotate(-150deg) saturate(200%)
    contrast(1);
  position: absolute;
  right: 0px;
}
.first_pic:hover {
  z-index: -1;
  filter: none;
}
.first_page .text {
  position: absolute;
  top: 40%;
  left: 15%;
}
.text h1 {
  font-size: 40px;
  margin-top: 30px;
}
.text h2 {
  font-size: 25px;
  margin-top: 30px;
}
.text img {
  width: 40px;
  margin-top: 5px;
  margin-right: 10px;
  filter: invert(100%);
}
.text img:hover {
  filter: none;
}
.second_pic {
  width: 20%;
  border-radius: 50%;
}
.profile {
  text-align: center;
  padding: 5%;
  height: 100vh;
}
/*.profile .text {
  width: 25%;
}*/
.profile p {
  margin: 3% 20%;
  font-size: 18px;
}
.work,
.act,
.hob {
  text-align: center;
}
.works h2 {
  margin: 50px 0px;
  text-decoration: underline;
}
.works p {
  font-size: 20px;
}
.work p {
  margin: 50px 0px;
}
.work_pic {
  width: 35%;
}
.work_pic2 {
  width: 25%;
}
.work_pic_small {
  width: 50%;
}
.work_pic_big {
  width: 20%;
}
.activities h2 {
  margin: 50px 0px;
  text-decoration: underline;
}
.activities p {
  font-size: 20px;
}
.activities p {
  margin: 50px 0px;
}
.act_pic {
  height: 250px;
  width: 420px;
}
.hobbies h2 {
  margin: 50px 0px;
  text-decoration: underline;
  text-align: left;
}
.hobbies p {
  font-size: 20px;
}
.hobbies p {
  margin: 50px 0px;
}
.img_draw {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
}
.draw {
  width: 85%;
}
</style>
