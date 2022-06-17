<template>
  <div class="layer-1">
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
    <div class="rain-drop">
      <img src="../assets/sakura-vector-png-4.png" width="15" />
    </div>
  </div>
</template>

<script>
export default {
  name: "BackGround",
};
</script>

<style>
.rain-drop {
  z-index: -10;
  color: #fff;
  position: fixed;
  top: -100px;
  width: 5px;
  height: 5px;
  opacity: 0.4;
}
.rain-drop:nth-child(2) {
  left: 10%;
  animation: rainFall 5s linear 2s infinite;
}
.rain-drop:nth-child(3) {
  left: 15%;
  animation: rainFall 10s linear 1s infinite;
}
.rain-drop:nth-child(4) {
  left: 35%;
  animation: rainFall 12s linear 0.1s infinite;
}
.rain-drop:nth-child(5) {
  left: 65%;
  animation: rainFall 20s linear 2s infinite;
}
.rain-drop:nth-child(6) {
  left: 80%;
  animation: rainFall 8s linear 4s infinite;
}
.rain-drop:nth-child(7) {
  left: 90%;
  animation: rainFall 16s linear 1.9s infinite;
}
.rain-drop:nth-child(8) {
  left: 82%;
  animation: rainFall 20s linear 0.8s infinite;
}
.rain-drop:nth-child(9) {
  left: 95%;
  animation: rainFall 10s linear 1s infinite;
}
.rain-drop:nth-child(10) {
  left: 53%;
  animation: rainFall 15s linear 2s infinite;
}
.rain-drop:nth-child(11) {
  left: 45%;
  animation: rainFall 8s linear 0.8s infinite;
}
.rain-drop:nth-child(12) {
  left: 5%;
  animation: rainFall 5s linear 0.2s infinite;
}
.rain-drop:nth-child(13) {
  left: 33%;
  animation: rainFall 20s linear 3s infinite;
}
.rain-drop:nth-child(14) {
  left: 66%;
  animation: rainFall 5s linear 2s infinite;
}
.rain-drop:nth-child(15) {
  left: 53%;
  animation: rainFall 5s linear 1.2s infinite;
}
@keyframes rainFall {
  0% {
    top: -100px;
  }
  50% {
    top: 100vh;
  }
  100% {
    top: 100vh;
  }
}
</style>
