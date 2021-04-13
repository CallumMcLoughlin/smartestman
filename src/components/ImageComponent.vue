<template>
  <div class="container box">
    <div class="image image is-16by9" >
      <img :src='require(`@/assets/${imgSrc}`)' :alt=imgHeader>
    </div>
    <p class="has-text-centered title is-2">{{ imgHeader }}</p>
    <p class="has-text-centered subtitle is-4">{{ imgText }}</p>
  </div>
</template>

<script>
export default {
  name: "ImageComponent",
  props: ["imgSrc", "imgHeader", "imgText"],
}
</script>