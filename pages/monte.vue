<template>
    <div v-shared-element:monte class="w3-content">
    <img
        v-shared-element:vue-bcg2="{
                         type: 'auto',
      easing: 'ease',
      duration: '300ms',
      endDuration: '100ms',
      compositeOnly: true,
      zIndex: 1000
        }"
      src="https://bigseventravel.com/wp-content/uploads/2019/07/augustin-de-montesquiou-RqMIFcDLeos-unsplash.jpg"
      alt="Vue.js logo"
    />
            <div class="w3-twothird w3-container">
          <h2>5 Terre</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
            dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex
            ea commodo consequat.
          </p>
        </div>
                <div class="w3-twothird w3-container">
          <h2>5 Terre</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
            dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex
            ea commodo consequat.
          </p>
        </div>
    <nuxt-link to="/" class="button">Close</nuxt-link>
  </div>
</template>

<style lang="scss" scoped>
img {
    width: 100%;
}
.home {
  padding: var(--sizing--5x) 15%;
  width: 100%;
  height: 100%;
  min-height: 100vh;
  background: hsl(199, 40%, 30%);
}
.button {
  width: 75%;
  height: 70px;
  display: flex;
  color: #fff;
  text-decoration: none;
  font-family: inherit;
  font-size: 1.25rem;
  justify-content: center;
  align-items: center;
  margin: var(--sizing--4x) auto;
  border-radius: 24px;
  background: hsl(148, 24%, 49%);
  &:hover {
    background: hsl(148, 25%, 55%);
  }
}
</style>