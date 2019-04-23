<template>
  <v-app>
    <v-content>
      <SuperiorToolbar />
      <MiddleText />
      <ThumbnailGrid />
    </v-content>
  </v-app>
</template>

<script>
import SuperiorToolbar from '@/components/SuperiorToolbar'
import MiddleText from '@/components/MiddleText'
import ThumbnailGrid from '@/components/ThumbnailGrid'

export default {
  name: 'app',
  components: {
    SuperiorToolbar,
    MiddleText,
    ThumbnailGrid
  }
}
</script>
