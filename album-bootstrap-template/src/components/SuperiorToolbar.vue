<template>
  <v-content>
    <v-expansion-panel >
      <v-expansion-panel-content class="secondary">
        <template v-slot:header>
          <div>
            <v-icon color="grey" left>photo_camera</v-icon>
            <span class="text-capitalize headline font-weight-medium white--text">Album</span>
          </div>
        </template>
        <template v-slot:actions>
          <v-icon large color="grey">menu</v-icon>
        </template>
        <v-card color="secondary">
          <v-card-text>
            <v-layout row wrap>
              <v-flex xs12 md8>
                <span class="pl-3 text-capitalize headline font-weight-medium white--text">About</span>
                <p class="px-3 subheading font-weight-light grey--text">
                  Add some information about the album below, the author, or any other background context. Make it a few sentences long so folks can pick up some informative tidbits. Then, link them off to some social networking sites or contact information.
                </p>
              </v-flex>
              <v-flex xs12 md4>
                <span class="pl-3 text-capitalize headline font-weight-medium white--text">Contact</span>
                <div class="px-3 title font-weight-light white--text">Follow on Twitter</div>
                <div class="px-3 title font-weight-light white--text">Like on Facebook</div>
                <div class="px-3 title font-weight-light white--text">Email me</div>
              </v-flex>
            </v-layout>
          </v-card-text>
        </v-card>
      </v-expansion-panel-content>
    </v-expansion-panel>
  </v-content>
</template>
