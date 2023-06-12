<template>
  <div class="home">
    <HeaderCarousel />
    <FrontCarousel/>
    <MidCarousel/>
    <SocmedCarousel/>
    <PatnerCarousel/>
    <FooterCarousel/>

  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import FrontCarousel from '@/components/FrontCarousel.vue'
import HeaderCarousel from '@/components/HeaderCarousel.vue'
import MidCarousel from '@/components/MidCarousel.vue'
import SocmedCarousel from '@/components/SocmedCarousel.vue'
import PatnerCarousel from '@/components/PatnerCarousel.vue'
import FooterCarousel from '@/components/FooterCarousel.vue'

export default {
  name: 'HomeView',
  components: {
    // HelloWorld
    // eslint-disable-next-line vue/no-unused-components
    HeaderCarousel,
    FrontCarousel,
    MidCarousel,
    // eslint-disable-next-line vue/no-unused-components
    SocmedCarousel,
    // eslint-disable-next-line vue/no-unused-components
    PatnerCarousel,
    // eslint-disable-next-line vue/no-unused-components
    FooterCarousel
  }
}
</script>
