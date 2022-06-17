<template>
  <div class="contact_page">
    <div class="row contact">
      <div class="row col-4">
        <div>
          <img src="../assets/tel.png" />
          099-7972275
        </div>
        <div>
          <img src="../assets/email.png" />
          61050228@kmitl.ac.th
        </div>
      </div>
      <div class="row col-4">
        <div>
          <a
            href="https://facebook.com/benyapha.musikarayakun?_rdc=1&_rdr"
            target="_blank"
          >
            <img src="../assets/fb.png" />
            Benyapha Musikarayakun
          </a>
        </div>
        <div>
          <a href="https://twitter.com/ButterBen2" target="_blank">
            <img src="../assets/tw.png" />
            @ButterBen2
          </a>
        </div>
      </div>
      <div class="row col-4">
        <div>
          <a href="https://www.instagram.com/butter_benyapha/" target="_blank">
            <img src="../assets/ig.png" />
            @butter_benyapha
          </a>
        </div>
        <div>
          <a href="https://www.instagram.com/butter_bendrawing/" target="_blank">
            <img src="../assets/ig.png" />
            @butter_bendrawing
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MyContact",
};
</script>

<style>
.contact_page {
  position: fixed;
  width: 100%;
  height: 10%;
  bottom: 0px;
  background: #fff;
  text-decoration-line: none;
  color: #000;
}
.contact {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  margin: 0px 5%;
}
.col-4 img {
  width: 30px;
  height: 30px;
}
.col-4 {
  display: grid;
}
</style>
