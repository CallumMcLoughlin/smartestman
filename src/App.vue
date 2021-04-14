<template>
  <div>
    <hero-component hero-title="The Smartest Man in New Zealand" hero-subtitle="Officially"/>
    <div class="container">
      <image-component img-src="Smartest_Man_In_New_Zealand.png" img-header="Smartest Man in New Zealand" img-text="Image of Smartest Man in New Zealand, Callum McLoughlin"/>
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