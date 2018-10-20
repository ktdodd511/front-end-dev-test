<template>

  <v-container fluid>
  <v-layout row wrap id="top">
    <img id="top-banner" src="../assets/igniter-logo-white.png"/>
  </v-layout>

<v-layout row>
  <v-carousel
  delimiter-icon="stop"
   prev-icon="mdi-arrow-left"
   next-icon="mdi-arrow-right">
  <v-carousel-item>
    <v-layout row>
      <v-flex xs12>
        <img class="banner-img" id="hero-img" src="../assets/hero-img.jpg"/>
      </v-flex>
    </v-layout>
  </v-carousel-item>
  <v-carousel-item>
    <v-layout row>
      <v-flex xs12>
        <img class="banner-img" src="../assets/iStock1.jpg"/>
      </v-flex>
    </v-layout>
  </v-carousel-item>
  <v-carousel-item>
    <v-layout row>
      <v-flex xs12>
        <img class="banner-img" src="../assets/iStock2.jpg"/>
      </v-flex>
    </v-layout>
  </v-carousel-item>
  </v-carousel>
</v-layout>

  <v-layout row wrap>
    <v-flex xs4 id="banner-text-div">
      <h1 id="banner-text">Eat Prawns Daintily</h1>
      <v-btn class="contact-btn">Contact</v-btn>
    </v-flex>
    <v-flex xs4 id="envelope">
      <img src="../assets/envelope-icon.svg"/>
    </v-flex>
  </v-layout>

  <v-layout row wrap class="page-icon-div">
    <v-flex xs1 class="page-icon-img">
      <img src="../assets/page-icon.svg"/>
    </v-flex>
    <v-flex xs5>
      <p class="page-icon-para">meow to be let in yet i shredded your linens for you, mark territory, or sit in box. You are a captive audience while sitting on the toilet, pet me</p>
    </v-flex>
    <v-flex xs1 class="page-icon-img">
      <img src="../assets/page-icon.svg"/>
    </v-flex>
    <v-flex xs5>
      <p class="page-icon-para">meow to be let in yet i shredded your linens for you, mark territory, or sit in box. You are a captive audience while sitting on the toilet, pet me</p>
    </v-flex>
  </v-layout>

  <v-layout row wrap class="page-icon-div">
    <v-flex xs1 class="page-icon-img">
      <img src="../assets/page-icon.svg"/>
    </v-flex>
    <v-flex xs5>
      <p class="page-icon-para">meow to be let in yet i shredded your linens for you, mark territory, or sit in box. You are a captive audience while sitting on the toilet, pet me</p>
    </v-flex>
    <v-flex xs1 class="page-icon-img">
      <img src="../assets/page-icon.svg"/>
    </v-flex>
    <v-flex xs5>
      <p class="page-icon-para">meow to be let in yet i shredded your linens for you, mark territory, or sit in box. You are a captive audience while sitting on the toilet, pet me</p>
    </v-flex>
  </v-layout>

  <v-layout row wrap>
    <v-flex xs12 class="text-xs-center">
      <img id="blue-banner-img" src="../assets/slanted-gradient-background.svg"/>
      <h2 id="blue-banner-text">Curl up and sleep on the freshly laundered towels gnaw the corn cob weigh eight pounds but take up a full-size bed, and destroy house in 5 seconds run in circles. Kitty power scratch hopped up on catnip stare at wall turn and meow stare at wall some more meow again continue staring or jump off balcony, onto stranger's head.</h2>
    </v-flex>
  </v-layout>

  <v-layout row wrap class="next-header">
    <v-flex xs12 class="text-xs-center">
      <h2><b>LOREM</b> IPSUM</h2>
    </v-flex>
  </v-layout>

  <v-layout row wrap class="margin-100">
    <v-flex xs6>
      <p>Curl up and sleep on the freshly laundered towels gnaw the corn cob weigh eight pounds but take up a full-size bed, and destroy house in 5 seconds run in circles. Kitty power scratch hopped up on catnip stare at wall turn and meow stare at wall some more meow again continue staring or jump off balcony, onto stranger's head.</p>
    </v-flex>
    <v-flex xs6>
      <v-btn class="contact-btn">Contact</v-btn>
    </v-flex>
  </v-layout>

  <v-layout row wrap id="contact-modal">
  <modal name="contact-modal">
    <form id="contact">
    <h3>LOREM IPSUM</h3>
    <fieldset>
      <input placeholder="Your name" type="text" tabindex="1" autofocus>
    </fieldset>
    <fieldset>
      <input placeholder="Your Email Address" type="email" tabindex="2">
    </fieldset>
    <fieldset>
      <input placeholder="Your Phone Number (optional)" type="tel" tabindex="3">
    </fieldset>
    <fieldset>
      <textarea placeholder="Type your message here...." tabindex="5"></textarea>
    </fieldset>
    <fieldset>
      <button name="submit" type="submit" class="contact-btn" data-submit="...Sending">Submit</button>
      <button id="close">Close</button>
    </fieldset>
    </form>
  </modal>
  </v-layout>

  <v-layout row wrap class="percent">
    <v-flex xs4>
      <h2 id="percent-value1">240%</h2>
      <p>Scratch me there, elevator butt touch my tail, i shred your hand purrrr so give me attention or face the wrath of my claws</p>
    </v-flex>
    <v-flex xs4>
      <h2 id="percent-value2">105%</h2>
      <p>Scratch me there, elevator butt touch my tail, i shred your hand purrrr so give me attention or face the wrath of my claws</p>
    </v-flex>
    <v-flex xs4>
      <h2 id="percent-value3">159%</h2>
      <p>Scratch me there, elevator butt touch my tail, i shred your hand purrrr so give me attention or face the wrath of my claws</p>
    </v-flex>
  </v-layout>

  <v-layout row wrap class="next-next-header">
    <v-flex xs12 class="text-xs-center">
      <h2><b>LOREM</b> IPSUM</h2>
    </v-flex>
  </v-layout>

  <v-layout row wrap class="bottom-div">
    <v-flex xs6>
      <h2>Lorem ipsum dolor sit amet</h2>
      <h3>Lorem ipsum dolor sit amet lorem</h3>
      <p>Disappear for four days and return home with an expensive injury; bite the vet kitten is playing with dead mouse sun bathe, but chase the pig around the house my slave human didn't give me any food so i pooped on the floor.</p>
    </v-flex>
    <v-flex xs6>
      <img src="../assets/img1.jpg"/>
    </v-flex>
  </v-layout>

  <v-layout row wrap class="next-bottom-div">
    <v-flex xs6>
      <img src="../assets/img2.jpg"/>
    </v-flex>
    <v-flex xs6>
      <h2>Lorem ipsum dolor sit amet</h2>
      <h3>Lorem ipsum dolor sit amet lorem</h3>
      <p>Disappear for four days and return home with an expensive injury; bite the vet kitten is playing with dead mouse sun bathe, but chase the pig around the house my slave human didn't give me any food so i pooped on the floor.</p>
    </v-flex>
  </v-layout>

  </v-container>

</template>

<script>
export default {
  methods: {
    show () {
      this.$modal.show('contact-modal')
    },
    hide () {
      this.$modal.hide('contact-modal')
    }
  },
  mounted () {
    $('.contact-btn').on('click', this.show),
    $('#close').on('click', this.hide)
  }
}
</script>
