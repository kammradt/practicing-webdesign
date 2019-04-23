<template>
  <div>
    <v-layout row wrap>
      <v-toolbar
        dark
        flat
        height="60"
        color="#343A40"
      >
        <v-btn flat :ripple='false'>
          <v-icon color="grey" left>photo_camera</v-icon>
          <span class="text-capitalize headline font-weight-medium">Album</span>
        </v-btn>
        <v-spacer/>
        <v-btn flat :ripple='false'>
          <v-icon large color="grey">menu</v-icon>
        </v-btn>
      </v-toolbar>
    </v-layout>
  </div>
</template>

<script>

export default {
  name: 'app',
}
</script>
