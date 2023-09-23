<template>
<div class="flex justify-center items-center">
  <div>
    <ContentDoc path="/blog/hello"></ContentDoc>
  </div>
</div>
</template>

<script setup lang="ts">
useHead({
  script: [
    { src: "https://identity.netlify.com/v1/netlify-identity-widget.js" },
  ]
})
</script>