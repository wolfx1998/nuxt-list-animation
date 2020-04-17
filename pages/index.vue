<template>
  <div class="home">

    <div class="w3-container w3-teal">
      <h1>List page transition</h1>
    </div>

    <div class="w3-content">

      <nuxt-link v-shared-element:terre to="/terre">
      <div class="w3-row w3-margin">

        <div class="w3-third">
          <img
          v-shared-element:vue-bcg1="{
            zIndex: 2
          }"
          src="https://dotravel.com/uploads/articles/95/april-holiday-destinations_3.jpg" style="width:100%;min-height:200px">
        </div>
        <div class="w3-twothird w3-container">
          <h2>5 Terre</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
            dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex
            ea commodo consequat.
          </p>
        </div>

      </div>
      </nuxt-link>
      <nuxt-link v-shared-element:monte to="/monte">
      <div class="w3-row w3-margin">

        <div class="w3-third">
          <img
          v-shared-element:vue-bcg2="{
            zIndex: 2
          }"
          src="https://bigseventravel.com/wp-content/uploads/2019/07/augustin-de-montesquiou-RqMIFcDLeos-unsplash.jpg" style="width:100%;min-height:200px">
        </div>
        <div class="w3-twothird w3-container">
          <h2>Monterosso</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
            dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex
            ea commodo consequat.
          </p>
        </div>

      </div>
      </nuxt-link>
      <div class="w3-row w3-margin">

        <div class="w3-third">
          <img
          src="https://www.azamara.com/sites/default/files/heros/1800x1000-why-azamara-new_0_0.jpg" style="width:100%;min-height:200px">
        </div>
        <div class="w3-twothird w3-container">
          <h2>Vernazza</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
            dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex
            ea commodo consequat.
          </p>
        </div>

      </div>
      <div class="w3-row w3-margin">

      </div>
    </div>
  </div>
</template>
