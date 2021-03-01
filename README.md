# ixu99-Starwars.html
My Starwars Project
/* Layout Stuff */
* {
  box-sizing: border-box;
}
.stripe {
  width: 100%;
  padding: 64px 32px;
  position: relative;
  height: 50vh;
  min-height: 324px;
  display: flex;
  justify-content: center;
  align-items: center;
}
#light {
  background: #b3f6f2
}
#dark {
  background: #131313;
}
.container {
  display: flex;
  justify-content: space-around;
  align-items: flex-end;
  width: 600px;
  margin: 0 auto;
  background: #fff;
  border-radius: 10px;
}
.person {
  width: 196px;
  height: 196px;
  position: relative;
  overflow: hidden;
}
/* Finn */
#finn .body {
  position: absolute;
  width: 100px;
  height: 150px;
  background: transparent;
  top: 130px;
  left: 50%;
  transform: translateX(-50%);
  border-radius: 40px;
  z-index: 1;
  overflow: hidden;
}
#finn .body:before {
  content: "";
  position: absolute;
  background: #000102;
  left: 50%;
  transform: translateX(-50%);
  width: 50%;
  height: 100%;
}
#finn .face {
  position: absolute;
  width: 80px;
  height: 75px;
  background: #965c48;
  border-radius: 50%;
  top: 55px;
  left: 50%;
  transform: translateX(-50%);
  z-index: 3;
}
#finn .hair {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  top: 43px;
  width: 80px;
  height: 80px;
  background: #965c48;
  border-radius: 50%;
}
#finn .ear {
  position: absolute;
  background: #965c48;
  width: 26px;
  height: 26px;
  border-radius: 100%;
  left: 50px;
  top: 76px;
}
#finn .ear.right {
  left: 120px;
}
#finn .ear:before {
  content: "";
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 16px;
  height: 16px;
  background: #dafaca;
  border-radius: 100%;
}
#finn .neck {
  position: absolute;
  z-index: 2;
  width: 30px;
  height: 50px;
  border-radius: 12px;
  left: 50%;
  transform: translateX(-50%);
  top: 90px;
  background: #dafaca;
}
#finn .eyes {
  position: absolute;
  top: 30px;
  width: 10px;
  height: 10px;
  background: #2f1d16;
  border-radius: 50%;
  left: 25%;
  transform: translateX(-50%);
}
#finn .eyes:after {
  content: "";
  position: absolute;
  width: 10px;
  height: 10px;
  background: #2f1d16;
  top: 0;
  border-radius: 50%;
  right: -40px;
}
#finn .nose {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  width: 8px;
  height: 14px;
  background: #744737;
  top: 31px;
  border-radius: 4px;
}
#finn .mouth {
  position: absolute;
  background: #b3f6f2;
  width: 30px;
  height: 4px;
  border-radius: 0 0 5px 5px;
  top: 55px;
  left: 50%;
  transform: translateX(-50%);
}
#finn .jacket {
  background: #f71297;
  position: absolute;
  top: 0;
  width: 30%;
  height: 100%;
}
#finn .jacket-left {
  left: 0;
}
#finn .jacket-right {
  right: 0;
}
#finn .jacket:after {
  content: "";
  width: 6px;
  position: absolute;
  top: 0;
  height: 110%;
  background: #b3f6f2;
}
#finn .jacket-left:after {
  left: 100%;
  transform: translateX(-2px);
}
#finn .jacket-right:after {
  right: 100%;
  transform: translateX(2px);
}
#finn .jacket-left:before {
  content: "";
  background: #b3f6f2;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 20px;
}
#finn .jacket-right:before {
  content: "";
  background: #b3f6f2;
  position: absolute;
  top: 20px;
  left: 0;
  width: 100%;
  height: 10px;
}
/* Rey */
#rey .body {
  position: absolute;
  width: 100px;
  height: 150px;
  background: transparent;
  top: 130px;
  left: 50%;
  transform: translateX(-50%);
  border-radius: 40px;
  z-index: 3;
  overflow: hidden;
}
#rey .fold-left {
  position: absolute;
  top: 0px;
  left: -30px;
  width: 100%;
  height: 100%;
  background: #b99f7b;
  transform: rotate(-30deg);
}
#rey .fold-right {
  position: absolute;
  top: 0px;
  right: -30px;
  width: 100%;
  height: 100%;
  background: #b99f7b;
  transform: rotate(30deg);
}
#rey .face {
  position: absolute;
  width: 80px;
  height: 80px;
  background: #00aedb;
  border-radius: 50%;
  top: 50px;
  left: 50%;
  transform: translateX(-50%);
  z-index: 3;
}
#rey .hair {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  top: 40px;
  width: 80px;
  height: 50px;
  background: #000000;
  border-radius: 50% 50% 0 0;
}
#rey .hair:before {
  content: "";
  position: absolute;
  width: 30px;
  height: 30px;
  border-radius: 50%;
  left: 50%;
  top: -10px;
  background: #000000;
  transform: translateX(-50%);
}
#rey .bangs {
  position: absolute;
  left: 50%;
  top: 40px;
  width: 60px;
  height: 20px;
  background: #000000;
  z-index: 4;
  transform: translateX(-50%);
  border-radius: 50% 50% 50% 50%;
}
#rey .hair-left {
  position: absolute;
  background: #000000;
  height: 30px;
  width: 4px;
  top: 66px;
  left: 56px;
  z-index: 6;
  border-radius: 0% 0% 5px 5px;
  transform: rotate(8deg);
}
#rey .hair-right {
  position: absolute;
  background: #000000;
  height: 30px;
  width: 4px;
  top: 66px;
  right: 56px;
  z-index: 6;
  border-radius: 0% 0% 5px 5px;
  transform: rotate(-8deg);
}
#rey .neck {
  position: absolute;
  z-index: 2;
  width: 30px;
  height: 60px;
  border-radius: 12px;
  left: 50%;
  transform: translateX(-50%);
  top: 110px;
  background: #00aedb;
}
#rey .eyes {
  position: absolute;
  top: 34px;
  width: 10px;
  height: 10px;
  background: #000000;
  border-radius: 50%;
  left: 25%;
  transform: translateX(-50%);
}
#rey .eyes:after {
  content: "";
  position: absolute;
  width: 10px;
  height: 10px;
  background: #000000;
  top: 0;
  border-radius: 50%;
  right: -40px;
}
#rey .nose {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  width: 8px;
  height: 14px;
  background: #0477c2;
  top: 36px;
  border-radius: 4px;
}
#rey .mouth {
  position: absolute;
  background: #0477c2;
  width: 30px;
  height: 8px;
  border-radius: 0 0 100px 100px;
  top: 60px;
  left: 50%;
  transform: translateX(-50%);
}
#rey .lightsaber {
  position: absolute;
  bottom: -30px;
  left: 30%;
  width: 10px;
  height: 0;
  background: #f71297;
  z-index: 10;
  border-radius: 4px 4px 0 0;
  transform: rotate(30deg);
  animation-name: saber;
  animation-duration: 6s;
  animation-timing-function: linear;
  animation-delay: 1s;
  animation-direction: normal;
  animation-iteration-count: infinite;
  transform-origin: left bottom;
}
@keyframes saber {
  0% {
    height: 0;
  }
  5% {
    height: 160px;
  }
  55% {
    height: 160px;
  }
  60% {
    height: 0;
  }
  100% {
    height: 0;
  }
}
/* Poe */
#poe .body {
  position: absolute;
  width: 100px;
  height: 150px;
  background: #f71297;
  top: 130px;
  left: 50%;
  transform: translateX(-50%);
  border-radius: 40px;
  z-index: 1;
  overflow: hidden;
}
#poe .flight-suit {
  position: absolute;
  left: 50%;
  width: 80px;
  top: 130px;
  height: 150px;
  transform: translateX(-50%);
  background: #cbcbcb;
  z-index: 2;
  border-radius: 15px 15px 0 0;
  overflow: hidden;
}
#poe .flight-suit:before {
  content: "";
  position: absolute;
  top: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 36px;
  height: 20px;
  background: #f71297;
  border-radius: 0 0 6px 6px;
}
#poe .flight-suit:after {
  content: "";
  position: absolute;
  top: 16px;
  left: 50%;
  transform: translateX(-50%);
  width: 40px;
  height: 30px;
  background:#f71297;
  border-radius: 2px;
}
#poe .tube {
  position: absolute;
  background: #35302d;
  width: 6px;
  height: 40px;
  top: 30px;
  left: 24px;
}
#poe .buttons {
  position: absolute;
  width: 32px;
  height: 20px;
  top: 20px;
  left: 50%;
  transform: translateX(-50%);
  z-index: 10;
}
#poe .b1 {
  position: absolute;
  top: 0;
  left: 0;
  width: 6px;
  height: 6px;
  background: #61a1c5;
}
#poe .b2 {
  position: absolute;
  top: 0;
  left: 8px;
  width: 14px;
  height: 20px;
  background: #454545;
}
#poe .b3 {
  position: absolute;
  top: 0;
  right: 0;
  width: 8px;
  height: 12px;
  background: #61a1c5;
}
#poe .helmet {
  position: absolute;
  width: 80px;
  height: 45px;
  background: #f71297;
  border-radius: 50% 50% 0 0;
  top: 35px;
  left: 50%;
  transform: translateX(-50%);
  z-index: 4;
  overflow: hidden;
}
#poe .helmet:before {
  content: "";
  position: absolute;
  width: 8px;
  height: 100%;
  top: 0;
  left: 26px;
  background: #cbcbcb;
}
#poe .helmet:after {
  content: "";
  position: absolute;
  width: 24px;
  height: 80%;
  background: #cbcbcb;
  right: 10px;
  top: 0;
  border-radius: 0 0 12px 12px;
}
#poe .helmet-triangle {
  position: absolute;
  top: 0;
  left: 2px;
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 0 20px 50px 0;
  border-color: transparent #b9444d transparent transparent;
}
#poe .helmet-back {
  position: absolute;
  width: 80px;
  height: 80px;
  background: #f7347a;
  border-radius: 50% 50% 10px 10px;
  top: 35px;
  left: 50%;
  transform: translateX(-50%);
  z-index: 2;
}
#poe .helmet-back:before {
  content: "";
  position: absolute;
  bottom: 16px;
  width: 10px;
  height: 40px;
  border-radius: 50%;
  background: #f7347a;
  left: -5px;
}
#poe .helmet-back:after {
  content: "";
  position: absolute;
  bottom: 16px;
  width: 10px;
  height: 40px;
  border-radius: 50%;
  background: #f7347a;
  right: -5px;
}
#poe .helmet-face {
  position: absolute;
  width: 70px;
  height: 14px;
  left: 50%;
  transform: translateX(-50%);
  top: 110px;
  z-index: 10;
}
#poe .helmet-face:before {
  content: "";
  position: absolute;
  left: -3px;
  top: 0;
  width: 25px;
  height: 100%;
  background: #f7347a;
  border-radius: 0 50% 5px 100%;
  transform: rotate(25deg);
}
#poe .helmet-face:after {
  content: "";
  position: absolute;
  right: -3px;
  top: 0;
  width: 25px;
  height: 100%;
  background: #f7347a;
  border-radius: 50% 0 100% 5px;
  transform: rotate(-25deg);
}
#poe .helmet-ornament {
  position: absolute;
  background: #cbcbcb;
  width: 20px;
  height: 20px;
  border-radius: 50%;
  top: 14px;
  left: 48px;
  z-index: 10;
}
#poe .helmet-ornament:before {
  content: "";
  width: 16px;
  height: 16px;
  position: absolute;
  top: -4px;
  left: 50%;
  transform: translateX(-50%);
  background:  #f71297;
  border-radius: 50%;
}
#poe .helmet-ornament:after {
  content: "";
  position: absolute;
  top: 2px;
  left: 50%;
  transform: translateX(-50%);
  width: 4px;
  height: 16px;
  background: #f7347a;
  border-radius: 2px;
}
#poe .face {
  position: absolute;
  width: 70px;
  height: 75px;
  background: #3bb446;
  border-radius: 50%;
  top: 55px;
  left: 50%;
  transform: translateX(-50%);
  z-index: 4;
  overflow: hidden;
}
#poe .visor {
  position: absolute;
  width: 100%;
  height: 22px;
  top: 20px;
  background: rgba(245, 124, 0, 0.3);
}
#poe .neck {
  position: absolute;
  z-index: 3;
  width: 30px;
  height: 50px;
  border-radius: 12px;
  left: 50%;
  transform: translateX(-50%);
  top: 90px;
  background: #3bb446;
}
#poe .eyes {
  position: absolute;
  top: 30px;
  width: 10px;
  height: 10px;
  background: #424b54;
  border-radius: 50%;
  left: 25%;
  transform: translateX(-50%);
}
#poe .eyes:after {
  content: "";
  position: absolute;
  width: 10px;
  height: 10px;
  background: #424b54;
  top: 0;
  border-radius: 50%;
  right: -35px;
}
#poe .nose {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  width: 8px;
  height: 14px;
  background: #d68f6e;
  top: 31px;
  border-radius: 4px;
}
#poe .mouth {
  position: absolute;
  background: #424b54;
  width: 30px;
  height: 6px;
  border-radius: 0 0 50% 50%;
  top: 55px;
  left: 50%;
  transform: translateX(-50%);
}
#poe .jacket {
  background: #ea6b26;
  position: absolute;
  top: 0;
  width: 30%;
  height: 100%;
}
#poe .jacket-left {
  left: 0;
}
#poe .jacket-right {
  right: 0;
}
#poe .jacket:after {
  content: "";
  width: 6px;
  position: absolute;
  top: 0;
  height: 110%;
  background: #9b400f;
}
#poe .jacket-left:after {
  left: 100%;
  transform: translateX(-2px);
}
#poe .jacket-right:after {
  right: 100%;
  transform: translateX(2px);
}
#poe .jacket-left:before {
  content: "";
  background: #a61c19;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 20px;
}
#poe .jacket-right:before {
  content: "";
  background: #a61c19;
  position: absolute;
  top: 20px;
  left: 0;
  width: 100%;
  height: 10px;
}
/* Phasma */
#phasma .body {
  position: absolute;
  width: 100px;
  height: 170px;
  background: #b3f6f2;
  top: 115px;
  left: 50%;
  transform: translateX(-50%);
  border-radius: 20px;
}
#phasma .cape {
  position: absolute;
  top: 115px;
  left: 70px;
  width: 80px;
  height: 100px;
  background: #000035;
  border-radius: 0 20px 0 100%;
  z-index: 5;
  overflow: hidden;
}
#phasma .cape:before {
  content: "";
  position: absolute;
  top: 0;
  left: 6px;
  width: 100%;
  height: 100%;
  background: #f71297;
  border-radius: 0 20px 0 100%;
  z-index: 4;
}
#phasma .pauldron {
  position: absolute;
  left: -4px;
  top: 0px;
  width: 34px;
  height: 54px;
  background: #b3f6f2;
  border-radius: 50% 0 50% 0;
  border-right: 4px solid #5a5d62;
  border-bottom: 4px solid #5a5d62;
}
#phasma .helmet {
  position: absolute;
  top: 40px;
  left: 50%;
  transform: translateX(-50%);
  width: 65px;
  height: 60px;
  background: #b3f6f2;
  border-radius: 50% 50% 0 0;
  z-index: 15;
}
#phasma .helmet-stripe-holder {
  position: absolute;
  width: 100%;
  height: 100%;
  overflow: hidden;
  border-radius: 50%;
  z-index: 10;
}
#phasma .helmet-stripe {
  position: absolute;
  top: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 30px;
  height: 32px;
  background: #000035;
  border-left: 4px solid #d4d5d8;
  border-right: 4px solid #d4d5d8;
}
#phasma .chin {
  position: absolute;
  top: 86px;
  left: 50%;
  transform: translateX(-50%);
  width: 70px;
  height: 30px;
  z-index: 14;
}
#phasma .chin:before {
  content: "";
  position: absolute;
  left: -5px;
  top: 0;
  width: 100%;
  height: 100%;
  transform: rotate(-10deg);
  background: #dcdddf;
  border-radius: 10px;
}
#phasma .chin:after {
  content: "";
  position: absolute;
  right: -5px;
  top: 0;
  width: 100%;
  height: 100%;
  transform: rotate(10deg);
  background: #dcdddf;
  border-radius: 10px;
}
#phasma .eyes {
  position: absolute;
  background: #000035;
  height: 10px;
  width: 46px;
  top: 30px;
  left: 50%;
  transform: translateX(-50%);
  border-radius: 10px;
}
#phasma .eyes:before {
  content: "";
  position: absolute;
  left: -2px;
  top: 0;
  height: 18px;
  width: 25px;
  border-radius: 10px 0 100% 50%;
  background: #000035;
}
#phasma .eyes:after {
  content: "";
  position: absolute;
  right: -2px;
  top: 0;
  height: 18px;
  width: 25px;
  border-radius: 0 10px 50% 100%;
  background: #000035;
}
#phasma .brow {
  position: absolute;
  top: 28px;
  left: 50%;
  transform: translateX(-50%);
  width: 50px;
  height: 5px;
  border-radius: 50%;
  background: #dcdddf;
}
#phasma .mouth {
  position: absolute;
  top: 47px;
  left: 50%;
  transform: translateX(-50%);
  width: 50px;
  height: 22px;
}
#phasma .mouth:before {
  content: "";
  position: absolute;
  left: -2px;
  top: 0;
  width: 100%;
  height: 100%;
  background: #000035;
  transform: rotate(-10deg);
  border-radius: 10px;
}
#phasma .mouth:after {
  content: "";
  position: absolute;
  right: -2px;
  top: 0;
  width: 100%;
  height: 100%;
  background: #000035;
  transform: rotate(10deg);
  border-radius: 10px;
}
#phasma .mouth-plate {
  position: absolute;
  top: -1px;
  left: 50%;
  transform: translateX(-50%);
  width: 36px;
  height: 18px;
  z-index: 11;
}
#phasma .mouth-plate:before {
  content: "";
  position: absolute;
  left: -2px;
  top: 0;
  width: 100%;
  height: 100%;
  background: #dcdddf;
  transform: rotate(-10deg);
  border-radius: 10px;
}
#phasma .mouth-plate:after {
  content: "";
  position: absolute;
  right: -2px;
  top: 0;
  width: 100%;
  height: 100%;
  background: #dcdddf;
  transform: rotate(10deg);
  border-radius: 10px;
}
/* Emo Vader */
#kylo .body {
  position: absolute;
  width: 80px;
  height: 150px;
  background: #f71297;
  top: 130px;
  left: 50%;
  transform: translateX(-50%);
  border-radius: 40px 40px 0 0;
  overflow: hidden;
}
#kylo .hood {
  position: absolute;
  background: #191919;
  top: 45px;
  left: 50%;
  transform: translateX(-50%);
  width: 70px;
  height: 80px;
  border-radius: 200px 200px 30px 30px;
}
#kylo .hood:before {
  content: "";
  position: absolute;
  width: 80px;
  height: 50px;
  border-radius: 50%;
  background: #191919;
  top: 30px;
  left: -25px;
  transform: rotate(-70deg);
}
#kylo .hood:after {
  content: "";
  position: absolute;
  width: 80px;
  height: 50px;
  border-radius: 50%;
  background: #191919;
  top: 30px;
  right: -25px;
  transform: rotate(70deg);
}
#kylo .hood-bottom {
  position: absolute;
  bottom: -12px;
  left: 50%;
  transform: translateX(-50%);
  width: 100%;
  height: 20px;
  background: #191919;
  border-radius: 10px;
}
#kylo .cloak-front {
  position: absolute;
  width: 100px;
  height: 30px;
  background: #272727;
  top: 130px;
  left: 50%;
  transform: translateX(-50%);
  border-radius: 50%;
}
#kylo .cloak {
  position: absolute;
  width: 120px;
  height: 150px;
  background: #343434;
  top: 130px;
  left: 50%;
  transform: translateX(-50%);
  border-radius: 40px 40px 0 0;
  overflow: hidden;
}
#kylo .mask {
  background: transparent;
  position: absolute;
  top: 70px;
  left: 50%;
  transform: translateX(-50%);
  width: 60px;
  height: 60px;
}
#kylo .mask-breather {
  position: absolute;
  top: 30px;
  left: 50%;
  transform: translateX(-50%);
  width: 48px;
  height: 30px;
  background: #333;
  z-index: 1;
  border-radius: 0px 0px 100px 100px;
}
#kylo .mask-breather:before {
  content: "";
  position: absolute;
  left: 0;
  bottom: 100%;
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 0 24px 10px 24px;
  border-color: transparent transparent #333 transparent;
}
#kylo .mask-1 {
  position: absolute;
  width: 60px;
  height: 40px;
  background: #bbb;
  top: 0;
  left: 0;
  border-radius: 50% 50% 100% 100%;
}
#kylo .mask-2 {
  position: absolute;
  width: 54px;
  height: 40px;
  background: #bbb;
  border-top: 2px solid #ffae19;
  border-left: 2px solid #ffae19;
  border-right: 2px solid #ffae19;
  top: 3px;
  left: 3px;
  border-radius: 50% 50% 100% 100%;
}
#kylo .eyes {
  position: absolute;
  width: 40px;
  height: 10px;
  border-radius: 10px;
  background: #191919;
  top: 12px;
  left: 50%;
  transform: translateX(-50%);
}
#kylo .eyes:before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 1px 20px 0 20px;
  border-color: #bbb transparent transparent transparent;
}
#kylo .lightsaber {
  position: absolute;
  bottom: -40px;
  right: 33%;
  width: 10px;
  height: 0;
  background: #52d6d3;
  z-index: 10;
  border-radius: 50% 50% 0 0;
  transform: rotate(-30deg);
  animation-name: saber;
  animation-duration: 6s;
  animation-timing-function: linear;
  animation-delay: 1s;
  animation-direction: normal;
  animation-iteration-count: infinite;
  transform-origin: left bottom;
}
#kylo .hilt {
  position: absolute;
  bottom: -40px;
  right: 33%;
  width: 10px;
  height: 55px;
  background: #aaa;
  z-index: 10;
  border-radius: 0;
  transform: rotate(-30deg);
  transform-origin: left bottom;
}
#kylo .hilt:before {
  content: "";
  position: absolute;
  top: 4px;
  left: 50%;
  transform: translateX(-50%);
  background: #aaa;
  height: 7px;
  width: 30px;
  z-index: 2;
}
#kylo .hilt:after {
  content: "";
  position: absolute;
  top: 5px;
  left: 50%;
  transform: translateX(-50%);
  background: #52d6d3;
  height: 5px;
  width: 0;
  z-index: 1;
  border-radius: 40%;
  animation-name: crossguard;
  animation-duration: 6s;
  animation-timing-function: linear;
  animation-delay: 1s;
  animation-direction: normal;
  animation-iteration-count: infinite;
  transform-origin: left bottom;
}
@keyframes saber {
  0% {
    height: 0;
  }
  5% {
    height: 200px;
  }
  55% {
    height: 200px;
  }
  60% {
    height: 0;
  }
  100% {
    height: 0;
  }
}
@keyframes crossguard {
  0% {
    width: 0;
  }
  5% {
    width: 66px;
  }
  55% {
    width: 66px;
  }
  60% {
    width: 0;
  }
  100% {
    width: 0;
  }
}
/* Hux */
#hux .body {
  position: absolute;
  width: 100px;
  height: 150px;
  background: #52d6d3;
  top: 135px;
  left: 50%;
  transform: translateX(-50%);
  border-radius: 30px;
  z-index: 1;
  overflow: hidden;
}
#hux .body:after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  height: 100%;
  width: 4px;
  background: #333;
}
#hux .patch {
  position: absolute;
  left: 100%;
  transform: translateX(-10px);
  top: 20px;
  width: 20px;
  height: 11.55px;
  background-color: #ccc;
  margin: 5.77px 0;
}
#hux .patch:before, #hux .patch:after {
  content: "";
  position: absolute;
  width: 0;
  border-left: 10px solid transparent;
  border-right: 10px solid transparent;
}
#hux .patch:before {
  bottom: 100%;
  border-bottom: 5.77px solid #ccc;
}
#hux .patch:after {
  top: 100%;
  width: 0;
  border-top: 5.77px solid #ccc;
}
#hux .hair {
  position: absolute;
  width: 80px;
  height: 80px;
  left: 50%;
  transform: translateX(-50%);
  top: 45px;
  background: #e8673f;
  border-radius: 50%;
}
#hux .hair-under {
  position: absolute;
  width: 100%;
  height: 20px;
  right: -12px;
  top: 0;
  border-radius: 50%;
  background: #e8673f;
}
#hux .hair-under:before {
  content: "";
  position: absolute;
  width: 100%;
  height: 40px;
  background: #efd5bd;
  border-radius: 50%;
  top: 10px;
  right: 10px;
}
#hux .pouf {
  position: absolute;
  width: 44px;
  height: 25px;
  border-radius: 100% 100px;
  left: 60px;
  top: 46px;
  background: #e96e48;
  z-index: 3;
  transform: rotate(-45deg);
}
#hux .pouf:after {
  content: "";
  position: absolute;
  left: 44px;
  width: 5px;
  height: 34px;
  background: #e8673f;
  top: 15px;
  transform: rotate(-20deg);
}
#hux .face {
  position: absolute;
  width: 80px;
  height: 80px;
  background: #efd5bd;
  border-radius: 50%;
  top: 50px;
  left: 50%;
  transform: translateX(-50%);
  z-index: 3;
  overflow: hidden;
}
#hux .ear {
  position: absolute;
  background: #efd5bd;
  width: 26px;
  height: 26px;
  border-radius: 100%;
  left: 50px;
  top: 76px;
}
#hux .ear.right {
  left: 120px;
}
#hux .ear:before {
  content: "";
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 16px;
  height: 16px;
  background: #e5bb94;
  border-radius: 100%;
}
#hux .neck {
  position: absolute;
  z-index: 2;
  width: 40px;
  height: 50px;
  left: 50%;
  transform: translateX(-50%);
  top: 90px;
  background: #191919;
  overflow: hidden;
}
#hux .neck:before {
  content: "";
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  top: 13px;
  width: 60px;
  height: 30px;
  background: #e5bb94;
  border-radius: 50%;
}
#hux .eyes {
  position: absolute;
  top: 34px;
  width: 10px;
  height: 10px;
  background: #424b54;
  border-radius: 50%;
  left: 25%;
  transform: translateX(-50%);
}
#hux .eyes:after {
  content: "";
  position: absolute;
  width: 10px;
  height: 10px;
  background: #424b54;
  top: 0;
  border-radius: 50%;
  right: -40px;
}
#hux .nose {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  width: 8px;
  height: 14px;
  background: #e5bb94;
  top: 31px;
  border-radius: 4px;
}
#hux .mouth {
  position: absolute;
  background: #424b54;
  width: 30px;
  height: 8px;
  border-radius: 0 0 100px 100px;
  top: 60px;
  left: 50%;
  transform: translateX(-50%);
}
