* {
  box-sizing: border-box;
    margin: 0;
  padding: 0;
}
body {
  font-family: 'Open Sans', serif;
  font-weight: 300;
  background: #030303;
  color: black;
}
.background {
  background-image: linear-gradient(to bottom,transparent 40%,rgba(0,0,0,0.95) 70%, #020202), url("https://www.mountainliving.com/content/uploads/2020/12/b/z/gordon-rusticextmtn-1.jpeg");
  width: 100vw;
  height: 100vh;
  background-position: top;
  z-index: 1;
  position: relative;
}
h1 {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%); 
  z-index: 100;
  font-family: 'Gruppo', cursive;
  text-transform: uppercase;
  letter-spacing: 0.5rem;
  font-size: 3rem;
  color: white;
  text-shadow: 2px 2px 5px;
}
.layer {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}
.layer-1 {
  background-image: linear-gradient(to bottom,transparent 50%,rgba(0, 0, 0,0.85) 70%, #020202), url("https://www.mountainliving.com/content/uploads/2020/12/b/z/gordon-rusticextmtn-1.jpeg");
  z-index: 70;
}
.layer-2 {
  background-image: linear-gradient(to bottom,transparent 30%,rgba(0,0,0,0.9) 80%, #020202), url("https://www.mountainliving.com/content/uploads/2020/12/b/z/gordon-rusticextmtn-1.jpeg");
  z-index: 80;
}
.layer-3 {
  background-image: 
    linear-gradient(to bottom,transparent 60%,rgba(0, 0,0,0.85), #020202), url("https://www.mountainliving.com/content/uploads/2020/12/b/z/gordon-rusticextmtn-1.jpeg");
  z-index: 90;
}
.content {
  font-size: 1.2rem;
  line-height: 1.7;
  position: relative;
  background-image: url("https://www.freevector.com/uploads/vector/preview/18962/30-01.jpg");
  background-size: cover;
  background-attachment: fixed;
}
.text {
  padding: 4rem 10rem 20rem 40rem;
}
.snowflake {
  position: absolute;
  z-index: 1000;
}
.snow-1 {
 width: 120px;
 height: 100px;
 left: 90%;
 top: 50%;
}
.snow-2 {
  width: 120px;
  height: 120px;
  left: 20%;
  top: 30%;
}
.snow-3 {
  width: 80px;
  height: 80px;
  left: 10%;
  bottom: 20%;
}
.snow-4 {
  width: 130px;
  height: 130px;
  bottom: 0;
  left: 31%;
}
.snow-5 {
  width: 110px;
  height: 110px;
  bottom: 0;
  left: 80%;
  -webkit-transform: scaleX(-1);
  transform: scaleX(-1);
}
.snow-6 {
  width: 70px;
  height: 70px;
  bottom: 30%;
  left: 20%;
}
.snow-7 {
  width: 120px;
  height: 120px;
  bottom: 35%;
  left: 15%;
  -webkit-transform: scaleX(-1);
  transform: scaleX(-1);
}
.snow-8 {
  width: 50px;
  height: 50px;
  bottom: 25%;
  left: 25%;
  -webkit-transform: scaleX(-1);
  transform: scaleX(-1);
}
.snow-9 {
  width: 70px;
  height: 70px;
  bottom: 35%;
  left: 30%;
}

@media only screen and (max-width: 1200px) {
  h1 {
    font-size: 2rem;
    letter-spacing: 0.1rem;
    text-align: center;
  }
  .rocks, .rock {
    display: none;
  }
  .text {
    padding: 0 3rem 5rem 3rem;
  }
}
