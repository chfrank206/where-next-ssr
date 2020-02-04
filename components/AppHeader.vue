<template>
  <header class="header">
    <div class="header-left">
          <nuxt-link to="/planYourTrip" class="header-nav-item nav-element">Plan Your Trip</nuxt-link>
          <nuxt-link to="/aboutMe" class="header-nav-item nav-element">About Me</nuxt-link>
    </div>
    <div class="header-center nav-element">
      <h1>Where Next Travel</h1>
    </div>
    <div class="header-right">
          <nuxt-link to="/contact" class="header-nav-item nav-element">Contact</nuxt-link>
          <nuxt-link to="/blog" class="header-nav-item nav-element">Blog</nuxt-link>
    </div>
  </header>
</template>

<script>
export default {
  name: "AppHeader"
};
</script>

<style>
.header {
  width: 100%;
  height: 50px;
  margin: auto;
  text-align: center;
}

.header-left {
display: inline-block;
justify-content: space-between;
float: left;
height: 100%;
padding-left: 10px;
}

.header-center {
display: inline-block;
justify-content: center;
text-align: center;
height: 100%;

}

.header-right {
display: inline-block;
justify-content: space-between;
float: right;
height: 100%;
padding-right: 10px;
}
</style>