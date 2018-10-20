<template>
  <div id="app">
    <router-view/>
  </div>

</template>

<script>
export default {
  name: 'App',
  }
</script>

<style>
#app {
  font-family: 'Roboto', sans-serif;
}

#top {
  background-color: blue;
  position: absolute;
  top: 0;
  left: 0;
  z-index: 999;
  width: 100%;
  height: 70px;
  margin-top: 0;
  padding-top: 0;
}

#top img {
  height: 60px;
  text-align: center;
  display: block;
  margin: auto;
}

.banner-img {
  height: 509px;
  width: 100%;
  position: absolute;
  top: 0;
  left: 0;
}

#banner-text {
  font-weight: bold;
  font-size: 48px;
}

#banner-text-div {
  margin-top: 350px;
  margin-left: 200px;
  z-index: 100;
  position: absolute;
  top: 0;
  left: 0;
  font-size: 40px !important;
  color: #fff;
}

#hero-img {
  opacity: 30%;
}

#blue-banner-img {
  position: absolute;
  left:0;
}

#envelope {
  position: absolute;
  top:0;
  left:0;
  z-index: 100;
  float: right;
}

#blue-banner-text {
  z-index: 100;
  position: absolute;
  color: white;
  margin-top: 100px;
  margin-left: 200px;
  margin-right: 200px;
}

.page-icon-div {
  margin: 50px;
  line-height: 20px;
}

.next-header {
  margin-top: 400px;
}

.next-header h2, .next-next-header h2 {
  font-size: 28px;
  color: #f36819;
}

.next-next-header {
  margin-top: 150px;
}

.page-icon-para {
  margin-right: 50px;
}

.margin-100 {
  margin: 100px;
  font-size: 14px;
  line-height: 20px;
}

.margin-100 p {
  margin-right: 100px;
  color: #283647;
}

.margin-100 button {
  margin-left: 100px;
}

.percent {
  margin: 100px;
}

.percent h2 {
  font-weight: bold;
  font-size: 55px;
  letter-spacing: 2px;
}

.percent p {
  color: #f36819;
  margin-right: 220px;
}

.margin-10 {
  margin-left: 10px;
}

.contact-btn {
  float: left;
  border-radius: 5px;
  background: linear-gradient(to right, #f36819, #f7931d) !important;
  color: #fff !important;
  letter-spacing: 2px;
  height: 40px;
  width: 215px;
}

.bottom-div {
  margin: 100px;
}

.bottom-div h2, .next-bottom-div h2 {
  color: #f36819;
  font-size: 28px;
}

.bottom-div h2 {
  margin-top: 100px;
}

.bottom-div h3 {
  color: #f7931d;
  font-size: 20px;
  letter-spacing: 2px;
  margin-bottom: 50px;
}

.bottom-div p {
  margin-right: 50px;
}

.bottom-div img {
  height: 350px;
  width: 705px;
  position: absolute;
  right: 0;
}

.next-bottom-div {
  margin-top: 200px;
}

.next-bottom-div h2 {
  margin-left: 75px;
  margin-top: 100px;
}

.next-bottom-div h3 {
  color: #f7931d;
  font-size: 20px;
  letter-spacing: 2px;
  margin-left: 75px;
}

.next-bottom-div p {
  margin-left: 75px;
  margin-right: 75px;
}

.next-bottom-div img {
  height: 350px;
  width: 705px;
  position: absolute;
  left: 0;
}

.v--modal-box.v--modal {
  height: 600px !important;
}


#contact input[type="text"],
#contact input[type="email"],
#contact input[type="tel"],
#contact input[type="url"],
#contact textarea,
#contact button[type="submit"] {
  font: 400 12px/16px "Roboto", Helvetica, Arial, sans-serif;
}

#contact {
  background: #F9F9F9;
  padding: 25px;
  box-shadow: 0 0 20px 0 rgba(0, 0, 0, 0.2), 0 5px 5px 0 rgba(0, 0, 0, 0.24);
}

#contact h3 {
  display: block;
  font-size: 30px;
  font-weight: 300;
  margin-bottom: 10px;
}

fieldset {
  border: medium none !important;
  margin: 0 0 10px;
  min-width: 100%;
  padding: 0;
  width: 100%;
}

#contact input[type="text"],
#contact input[type="email"],
#contact input[type="tel"],
#contact input[type="url"],
#contact textarea {
  width: 100%;
  border: 1px solid #ccc;
  background: #FFF;
  margin: 0 0 5px;
  padding: 10px;
}

#contact input[type="text"]:hover,
#contact input[type="email"]:hover,
#contact input[type="tel"]:hover,
#contact input[type="url"]:hover,
#contact textarea:hover {
  -webkit-transition: border-color 0.3s ease-in-out;
  -moz-transition: border-color 0.3s ease-in-out;
  transition: border-color 0.3s ease-in-out;
  border: 1px solid #aaa;
}

#contact textarea {
  height: 100px;
  max-width: 100%;
  resize: none;
}

#contact input:focus,
#contact textarea:focus {
  outline: 0;
  border: 1px solid #aaa;
}

::-webkit-input-placeholder {
  color: #888;
}

:-moz-placeholder {
  color: #888;
}

::-moz-placeholder {
  color: #888;
}

:-ms-input-placeholder {
  color: #888;
}

#close {
  margin-left: 50px;
}


</style>
