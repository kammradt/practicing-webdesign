<template>
  <v-content>
    <v-layout align-center justify-center row>
      <v-flex xs12 text-xs-center my-5>
        <p class="font-weight-light display-1">
          Album example
        </p>
        <v-flex xs12 md4 offset-md4>
          <p class="px-3 title font-weight-light grey--text">
            Something short and leading about the collection below—its contents, the creator, etc. Make it short and sweet, but not too short so folks don't simply skip over it entirely.
          </p>
        </v-flex>
        <Popup />
        <v-menu offset-y>
          <v-btn slot="activator">
            <v-icon left>expand_more</v-icon>
            <span>Secondary action</span>
          </v-btn>
          <v-list>
            <v-list-tile>
              <v-list-tile-title>Item 1</v-list-tile-title>
            </v-list-tile>
            <v-list-tile>
              <v-list-tile-title>Item 2</v-list-tile-title>
            </v-list-tile>
            <v-list-tile>
              <v-list-tile-title>Item 5</v-list-tile-title>
            </v-list-tile>
          </v-list>
        </v-menu>
      </v-flex>
    </v-layout>
  </v-content>
</template>

<script>
import Popup from '@/components/Popup'
export default {
  components: {
    Popup,
  }
}
</script>

