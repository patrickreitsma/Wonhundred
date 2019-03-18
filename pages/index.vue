<template>
  <div>
    <index-Nav />
    <index-Header />
    <index-Homepicture />
    <index-Fotobox1 />
    <index-Slideshow1 />
    <index-Greencontent />
    <index-Slideshow2 />
    <index-Fotobox2 />
    <index-Footer />
  </div>
</template>

<script>
import Nav from '@/components/Nav.vue'
import Header from '@/components/Header.vue'
import Homepicture from '@/components/Homepicture.vue'
import Fotobox1 from '@/components/Fotobox1.vue'
import Slideshow1 from '@/components/Slideshow1.vue'
import Greencontent from '@/components/Greencontent.vue'
import Fotobox2 from '@/components/Fotobox2.vue'
import Slideshow2 from '@/components/Slideshow2.vue'
import Footer from '@/components/Footer.vue'

export default {
  components: {
    'index-Nav': Nav,
    'index-Header': Header,
    'index-Homepicture': Homepicture,
    'index-Fotobox1': Fotobox1,
    'index-Slideshow1': Slideshow1,
    'index-Greencontent': Greencontent,
    'index-Slideshow2': Slideshow2,
    'index-Fotobox2': Fotobox2,
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
