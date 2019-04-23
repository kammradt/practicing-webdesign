<template>
  <v-app>
    <v-content>
      <SuperiorToolbar />
      <MiddleText />
    </v-content>
  </v-app>
</template>

<script>
import SuperiorToolbar from '@/components/SuperiorToolbar'
import MiddleText from '@/components/MiddleText'

export default {
  name: 'app',
  components: {
    SuperiorToolbar,
    MiddleText
  }
}
</script>
