<template>
  <Layout>
    <div class="columns is-multiline">
      <!-- Landing Page -->
      <div class="column is-12 has-text-centered">
        <section class="section has-background-light" style="padding-top:50px;">
          <h3 class="title is-1">
            Completely Free & Open Source Template
            <br />for Startups
          </h3>
          <p class="subtitle is-5" style="max-width:60rem;margin:0 auto;">
            The Modern Look & Feel with Seamless Technology 'Gridsome', A Free Responsive Startup Template made with
            <a href="https://www.bulma.io">
              Bulma
            </a>
            You can easily modify the template with your company's primary color, and all the illustrations are from @undraw.
          </p>
          <div class="section">
            <div class="buttons is-centered">
              <a class="button is-primary is-large">Get Started -></a>
              <a class="button is-primary is-outlined is-large">Contact Us</a>
            </div>
          </div>
          <img src="../../static/cover-hero.svg" alt width="700" style="margin-top:-50px;" />
        </section>
        <div style="height: 250px; overflow: hidden;margin-top:-200px;" ><svg viewBox="0 0 500 150" preserveAspectRatio="none" style="height: 100%; width: 100%;"><path d="M-88.37,127.40 C150.00,150.00 349.20,-49.99 603.49,106.67 L500.00,150.00 L0.00,150.00 Z" style="stroke: none; fill: #fff;"></path></svg></div>
      </div>

      <!-- Features -->
      <div class="column is-12">
        <section class="has-text-centered" style="padding-bottom:60px;">
          <span class="tag is-light is-primary is-large">FEATURES</span>
          <h3 class="title is-2" style="margin-top:30px;">Some of the Features</h3>
          <p style="max-width:60rem;margin:0 auto;">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique dicta vitae est quas possimus quibusdam ea commodi? Voluptates atque hic blanditiis, vitae fugiat saepe magni ea laudantium sunt, velit voluptas?</p>
        </section>
      </div>
      <div class="column">
        <div class="columns" style="padding-bottom:50px;">
      <div class="column has-text-centered">
        <ApertureIcon size="5x"/>
        <h3 class="is-size-4 has-text-dark has-text-weight-bold">Sample Text</h3>
        <p class="has-text-grey" style="padding:0px 5px;">Some Sample Text, put anything here</p>
        <div class="has-text-primary has-text-bold is-size-5" style="margin-top:10px;">Learn More -></div>
      </div>
      <div class="column has-text-centered">
        <ApertureIcon size="5x"/>
        <h3 class="is-size-4 has-text-dark has-text-weight-bold">Sample Text</h3>
        <p class="has-text-grey" style="padding:0px 5px;">Some Sample Text, put anything here</p>
        <div class="has-text-primary has-text-bold is-size-5" style="margin-top:10px;">Learn More -></div>
      </div>
      <div class="column has-text-centered">
        <ApertureIcon size="5x"/>
        <h3 class="is-size-4 has-text-dark has-text-weight-bold">Sample Text</h3>
        <p class="has-text-grey" style="padding:0px 5px;">Some Sample Text, put anything here</p>
        <div class="has-text-primary has-text-bold is-size-5" style="margin-top:10px;">Learn More -></div>
      </div>
      <div class="column has-text-centered">
        <ApertureIcon size="5x"/>
        <h3 class="is-size-4 has-text-dark has-text-weight-bold">Sample Text</h3>
        <p class="has-text-grey" style="padding:0px 5px;">Some Sample Text, put anything here</p>
        <div class="has-text-primary has-text-bold is-size-5" style="margin-top:10px;">Learn More -></div>
      </div>
    </div>
    </div>
    </div>
  </Layout>
</template>

<script>
import { ApertureIcon } from 'vue-feather-icons'

export default {
  metaInfo: {
    title: "Startup Starter - Gridsome + Bulma | Justaashir"
  },
  data(){
    return{

    }
  },
  components:{
    ApertureIcon
  }
};
</script>

<style>
</style>
