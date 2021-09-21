<template>
  <div class="container">

    <div class="logo"><nuxt-link to="/">MyWebsite</nuxt-link></div>

    <div class="navigation">
      <div class="nav">
        <div class="nav-item">
          <nuxt-link class="link" to="/works">Works</nuxt-link>
        </div>
        <div class="nav-item">
          <nuxt-link class="link" to="/blog">Blog</nuxt-link>
        </div>
        <div class="nav-item">
          <nuxt-link class="link" to="/contact">Contact</nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {

}
</script>

<style>
.navigation {
  
}
.link {
  text-decoration: none;
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 29px;
  color: #000000;
}

</style>