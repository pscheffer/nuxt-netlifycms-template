<template>
  <div class="container">
    <h1>Hi.</h1>
  </div>
</template>

<script>
  export default {
    head() {
      return {
        script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
      }
    }
  }
</script>