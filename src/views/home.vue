<template>
  <div id="home" class="home-container">
    <app-navbar link1="Home" link3="Bill Gates Memes"></app-navbar>
    <app-hero></app-hero>
    <app-features1></app-features1>
    <app-cta action1="Get Started"></app-cta>
    <app-steps></app-steps>
    <app-stats3 stats3Id="Stats3">
      <template v-slot:stat1>
        <div class="home-fragment1">
          <span class="home-text1">10.000.000</span>
        </div>
      </template>
      <template v-slot:stat2>
        <div class="home-fragment2"><span class="home-text2">0.3%</span></div>
      </template>
      <template v-slot:stat3>
        <div class="home-fragment3">
          <span class="home-text3">
            Optimism
            <span v-html="rawh8v4"></span>
          </span>
        </div>
      </template>
      <template v-slot:stat4>
        <div class="home-fragment4">
          <span class="home-text4">
            0x62fC0b85B64959B16D16c69d9075b5acD0AD034f
          </span>
        </div>
      </template>
      <template v-slot:heading1>
        <div class="home-fragment5">
          <span class="home-text5">
            Tokenomics
            <span v-html="rawvsfu"></span>
          </span>
        </div>
      </template>
      <template v-slot:stat1Description>
        <div class="home-fragment6">
          <span class="home-text6">Total Supply</span>
        </div>
      </template>
      <template v-slot:stat2Description>
        <div class="home-fragment7"><span class="home-text7">Fee Tier</span></div>
      </template>
      <template v-slot:stat3Description>
        <div class="home-fragment8"><span class="home-text8">Network</span></div>
      </template>
      <template v-slot:stat4Description>
        <div class="home-fragment9"><span class="home-text9">Contract</span></div>
      </template>
    </app-stats3>
    <app-testimonial
      content1="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
      author1Position="Crypto Enthusiast"
      author4Position="Crypto Enthusiast"
    ></app-testimonial>
    <app-footer socialLinkTitleCategory="Follow Us - SOON"></app-footer>
  </div>
</template>

<script>
import AppNavbar from '../components/navbar'
import AppHero from '../components/hero'
import AppFeatures1 from '../components/features1'
import AppCta from '../components/cta'
import AppSteps from '../components/steps'
import AppStats3 from '../components/stats3'
import AppTestimonial from '../components/testimonial'
import AppFooter from '../components/footer'

export default {
  name: 'Home',
  components: {
    AppNavbar,
    AppHero,
    AppFeatures1,
    AppCta,
    AppSteps,
    AppStats3,
    AppTestimonial,
    AppFooter,
  },
  data() {
    return {
      rawh8v4: ' ',
      rawvsfu: ' ',
    }
  },
  metaInfo: {
    title: 'BILL GATES MEME COIN',
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.home-fragment1 {
  display: contents;
}
.home-text1 {
  display: inline-block;
}
.home-fragment2 {
  display: contents;
}
.home-text2 {
  display: inline-block;
}
.home-fragment3 {
  display: contents;
}
.home-text3 {
  display: inline-block;
}
.home-fragment4 {
  display: contents;
}
.home-text4 {
  display: inline-block;
}
.home-fragment5 {
  display: contents;
}
.home-text5 {
  display: inline-block;
}
.home-fragment6 {
  display: contents;
}
.home-text6 {
  display: inline-block;
}
.home-fragment7 {
  display: contents;
}
.home-text7 {
  display: inline-block;
}
.home-fragment8 {
  display: contents;
}
.home-text8 {
  display: inline-block;
}
.home-fragment9 {
  display: contents;
}
.home-text9 {
  display: inline-block;
}
</style>
