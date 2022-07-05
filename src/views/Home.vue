<template>
  <div class="home">
    <Hero></Hero>
    <Nick></Nick>
    <Work></Work>
    <CTA></CTA>
  </div>
</template>

<script>
// @ is an alias to /src
import Hero from '@/components/Hero.vue'
import Nick from '@/components/Nick.vue'
import Work from '@/components/Work.vue'
import CTA from '@/components/CTA.vue'

export default {
  name: 'Home',
  components: {
    Hero,
    Nick,
    Work,
    CTA
  }
}
</script>
