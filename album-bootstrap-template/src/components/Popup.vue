<template>
  <v-dialog max-width="600px" v-model="dialog">
    <v-btn flat slot="activator" class="secondary">Primary action</v-btn>
    <v-card>
      <v-card-title>
        <span class="font-weight-light display-1">Hello, this is an example!!</span>
      </v-card-title>
      <v-card-text>
        <v-form class="px-3">
          <v-text-field
            label="Title"
            prepend-icon="folder"
            color="pink darken-1"
          />
          <v-text-field
            label="Description"
            prepend-icon="edit"
            color="pink darken-1"
            textarea
          />
          <v-btn
            dark
            color="secondary"
            class="mx-0 mt-3"
            v-text="'Confirm'"
            @click="dialog = !dialog"
          />
        </v-form>
      </v-card-text>
    </v-card>
  </v-dialog>
</template>

<script>
export default {
  data() {
    return {
      dialog: false
    }
  }
}
</script>
