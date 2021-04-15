<template>
  <div class="tile is-ancestor">
    <div class="tile is-4 is-vertical is-parent">
      <div class="tile is-child box">
        <p class="title">Who is the Smartest Man in New Zealand</p>
        <p class="has-text-justified">
          The picture on this page is about the <strong>Smartest Man in New Zealand</strong> and also the <strong>Smartest Man in Christchurch</strong>.
          Christchurch is a city within New Zealand. The man depicted on this page is the most clever, bright, intelligent, sharp, quick-witted,
          nimble-witted, astute, apt, able, well educated, well read, perceptive man in Christchurch, New Zealand.
        </p>
      </div>
      <div class="tile is-child box">
        <p class="title">Smartest Man in Christchurch</p>
        <p class="has-text-justified"><strong>The Smartest Man in Christchurch</strong>, is of course the smartest man in Christchurch, New Zealand.</p>
      </div>
    </div>
    <div class="tile is-parent">
      <div class="tile is-child box">
        <p class="title">Description of The Smartest Man in New Zealand</p>
        <p class="has-text-justified">The following is a (non comprehensive) list of dumber people than the smartest man in New Zealand.</p>
        <div class="container">
          <b-menu>
            <b-menu-list label="Dumber People than The Smartest Man in Christchurch">
              <b-menu-item v-for="person in dumbPeople" :key="person.name" :label=person.name>
              </b-menu-item>
            </b-menu-list>
          </b-menu>
        </div>
        <p class="has-text-justified">
          This man is so smart that he is light-years ahead of any of the previously mentioned people. The man pictured on this page
          is also well-dressed, fashionable, stylish, modish, elegant, bright, spotless, clean, snazzy and sharp.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TileComponent",
  data: () => {
    return {
      dumbPeople: [
        { name: "Stephen Hawking" },
        { name: "Albert Einstein" },
        { name: "Isaac Newton" },
        { name: "Nikola Tesla" },
        { name: "Johannes Kepler" },
      ]
    }
  }
}
</script>