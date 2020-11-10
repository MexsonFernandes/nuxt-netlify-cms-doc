<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">nuxt-netlify-doc</h1>
    </div>
  </div>
</template>

<script>
export default {
  head() {
    return {
      script: [
        { src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' },
      ],
    }
  },
}
</script>
