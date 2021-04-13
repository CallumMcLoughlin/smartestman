<template>
  <div>
    <hero-component hero-title="The Smartest Man in Christchurch" hero-subtitle="New Zealand"/>
    <div class="container">
      <image-component img-src="Smartest_Man_In_Christchurch.png" img-header="Smartest Man in Christchurch" img-text="Image of Smartest Man in Christchurch, New Zealand"/>
      <tile-component/>
    </div>
    <footer-component/>
  </div>
</template>

<script>
import ImageComponent from "@/components/ImageComponent";
import HeroComponent from "@/components/HeroComponent";
import TileComponent from "@/components/TileComponent";
import FooterComponent from "@/components/FooterComponent";

export default {
  name: 'App',
  components: {
    FooterComponent,
    TileComponent,
    HeroComponent,
    ImageComponent
  }
}
</script>