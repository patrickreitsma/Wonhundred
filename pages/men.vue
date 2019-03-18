<template>
  <div>
    <men-Nav />
    <men-Headermen />
    <men-Fotobox-men />
    <men-Slideshow-men />
    <men-Fotobox2-men />
    <men-More-men />
    <index-Footer />
  </div>
</template>

<script>
import Nav from '@/components/Nav.vue'
import Headermen from '@/components/menpage/Headermen.vue'
import Fotobox from '@/components/menpage/Fotobox-men.vue'
import Slideshow from '@/components/menpage/Slideshow-men.vue'
import Fotobox2 from '@/components/menpage/Fotobox2-men.vue'
import More from '@/components/menpage/More-men.vue'
import Footer from '@/components/Footer.vue'

export default {
  components: {
    'men-Nav': Nav,
    'men-Headermen': Headermen,
    'men-Fotobox-men': Fotobox,
    'men-Slideshow-men': Slideshow,
    'men-Fotobox2-men': Fotobox2,
    'men-More-men': More,
    'index-Footer': Footer
  },
  data() {
    return {
    }
  }
}
</script>
<style lang="scss">
</style>
