<template>
  <header class="header">
    <h1>Herding Cats Travel App</h1>
    <h2>Final Project for Coding Bootcamps Europe Web Developer Training</h2>
    <h3>April 2024</h3>
  </header>
  <main class="main-container">
    <div class="img-container"><ScreenShots /></div>
    <article class="text-container">
      <IntroText />
    </article>
  </main>
</template>

<script>
import ScreenShots from '@/components/ScreenShots.vue'
import IntroText from '@/components/IntroText.vue'
export default {
  components: {
    ScreenShots,
    IntroText
  }
}
</script>
