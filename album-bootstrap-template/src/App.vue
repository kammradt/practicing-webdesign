<template>
  <v-app>
    <v-content>
      <SuperiorToolbar />
      <MiddleText />
      <ThumbnailGrid />
      <Footer />
    </v-content>
  </v-app>
</template>

<script>
import SuperiorToolbar from '@/components/SuperiorToolbar'
import MiddleText from '@/components/MiddleText'
import ThumbnailGrid from '@/components/ThumbnailGrid'
import Footer from '@/components/Footer'

export default {
  name: 'app',
  components: {
    SuperiorToolbar,
    MiddleText,
    ThumbnailGrid,
    Footer
  }
}
</script>
