<template>
  <section class="container">
    <script type="text/javascript" src="https://identity.netlify.com/v1/netlify-identity-widget.js"></script>
    <div>
      <app-logo/>
      <h1 class="title">
        LIVEGLU LOGIN
      </h1>
      <h2 class="subtitle">
        Frank is so cool.
      </h2>
      
      <div data-netlify-identity-button>Let's get started</div>
    </div>
  </section>
        <div data-netlify-identity-button>Let's get started</div>

</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

