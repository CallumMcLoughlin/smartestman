<template>
  <div>
    <section class="hero is-small is-primary">
      <div class="hero-body">
        <p class="title">
          {{heroTitle}}
        </p>
        <p class="subtitle">
          {{heroSubtitle}}
        </p>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "HeroComponent",
  props: ["heroTitle", "heroSubtitle"],
}
</script>