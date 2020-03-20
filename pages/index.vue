<template>
  <v-content>
    <v-container>
      <v-row justify="center">
        <v-col cols="xl-8">
          <v-container class="hero">
            <v-row justify="center">
              <v-col cols="12" xl="5" lg="5" md="5" align-self="center">
                <h1 class="font-weight-black primary--text float-left float-md-none mr-5 mr-md-0">DIVI</h1>
                <p>Das beliebteste WordPress Theme der Welt und der ultimative WordPress Page Builder</p>
              </v-col>
              <v-col cols="12" xl="7" lg="7" md="7" align-self="center">
                <video id="video1" class="card card-full-bleed current-item" width="100%" autoplay="" loop="" muted="" playsinline="">
                  <source data-src="https://res.cloudinary.com/j0e/video/upload/v1584557707/build_i9ixup.mp4" video-src="https://res.cloudinary.com/j0e/video/upload/v1584557707/build_i9ixup.mp4" type="video/mp4" src="https://res.cloudinary.com/j0e/video/upload/v1584557707/build_i9ixup.mp4">
                </video>
              </v-col>
            </v-row>
            <ctaButtonComp />
          </v-container>

          <p>Geile Sache von Joe.</p>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tenetur ut blanditiis incidunt alias esse quia modi provident illum beatae, eaque ipsa reiciendis dolorum autem odit voluptate officiis hic sed officia!
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure qui iste quaerat officiis placeat maiores, aliquid commodi temporibus recusandae facilis odit sed tempore nobis eum, soluta, necessitatibus quam neque vitae.
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Facere facilis repellendus, ratione officiis praesentium voluptates aspernatur quae id nemo saepe vel enim illum eos ipsam earum! Omnis maiores vitae quam?
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente in inventore placeat, laboriosam, eligendi eum eaque molestias unde illo non blanditiis sed totam esse exercitationem dignissimos harum. Laudantium, nam ut?
          </p>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tenetur ut blanditiis incidunt alias esse quia modi provident illum beatae, eaque ipsa reiciendis dolorum autem odit voluptate officiis hic sed officia!
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure qui iste quaerat officiis placeat maiores, aliquid commodi temporibus recusandae facilis odit sed tempore nobis eum, soluta, necessitatibus quam neque vitae.
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Facere facilis repellendus, ratione officiis praesentium voluptates aspernatur quae id nemo saepe vel enim illum eos ipsam earum! Omnis maiores vitae quam?
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente in inventore placeat, laboriosam, eligendi eum eaque molestias unde illo non blanditiis sed totam esse exercitationem dignissimos harum. Laudantium, nam ut?
          </p>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tenetur ut blanditiis incidunt alias esse quia modi provident illum beatae, eaque ipsa reiciendis dolorum autem odit voluptate officiis hic sed officia!
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure qui iste quaerat officiis placeat maiores, aliquid commodi temporibus recusandae facilis odit sed tempore nobis eum, soluta, necessitatibus quam neque vitae.
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Facere facilis repellendus, ratione officiis praesentium voluptates aspernatur quae id nemo saepe vel enim illum eos ipsam earum! Omnis maiores vitae quam?
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente in inventore placeat, laboriosam, eligendi eum eaque molestias unde illo non blanditiis sed totam esse exercitationem dignissimos harum. Laudantium, nam ut?
          </p>
          <v-container class="heroBottom">
            <h2 class="font-weight-medium text-center">Mehr Kunden gewinnen mit<br />DIVI</h2>
            <v-row justify="center">
              <v-col>
                <ctaButtonComp />
              </v-col>
            </v-row>
          </v-container>
        </v-col>
      </v-row>
    </v-container>
  </v-content>
</template>

<script>
import ctaButtonComp from "~/components/ctaButtonComp"

export default {
  components: {
    ctaButtonComp
  },  
};
</script>

<style>
  .hero h1 {
    font-size: 10vw;
    font-weight: 900;
    line-height: 1.2em;
    margin-bottom: .2em;
  }
  .hero p {
    font-size: 34px;
    font-weight: 400;
    line-height: 1.2em;
    margin-bottom: .2em;
    color: #b142ec;
  }
  .heroBottom {
    margin: 120px 0;
    font-size: 3vw;
  }
</style>