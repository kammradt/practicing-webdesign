<template>
  <v-content>
    <v-flex xs12 grey lighten-1>
      <v-container grid-list-md>
        <v-layout row wrap>
          <v-flex v-for="card in cards" :key="card.title" xs12 md4 pa-3>
            <v-card>
              <v-flex xs12>
                <v-img src="https://cdn.vuetifyjs.com/images/parallax/material2.jpg"/>
              </v-flex>
              <v-card-text>
                {{ card.content }}
              </v-card-text>
            </v-card>
          </v-flex>
        </v-layout>
      </v-container>
    </v-flex>
  </v-content>
</template>

<script>
export default {
  data() {
    return {
      cards: [
        {title: 'My title 1', content: 'Sed ut. Dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore.'},
        {title: 'My title 2', content: 'Sed ut. Dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore.'},
        {title: 'My title 3', content: 'Sed ut. Dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore.'},
        {title: 'My title 4', content: 'Sed ut. Dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore.'},
        {title: 'My title 5', content: 'Sed ut. Dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore.'},
        {title: 'My title 6', content: 'Sed ut. Dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore.'},
        {title: 'My title 7', content: 'Sed ut. Dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore.'},
        {title: 'My title 8', content: 'Sed ut. Dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore.'},
        {title: 'My title 9', content: 'Sed ut. Dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore.'},
      ]
    }
  }
}
</script>