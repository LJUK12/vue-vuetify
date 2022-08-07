<template>
    <v-container
    fluid
    >
      <v-card>
        <v-row dense>
          <v-col
          cols="auto">
            <v-card
            class="pa-3"
            outlined>
            col
            </v-card>
          </v-col>
          <v-spacer/>
            <v-col>
            <v-card
            class="pa-3"
            outlined>
            col
            </v-card>
          </v-col>
            <v-col>
            <v-card
            class="pa-3"
            outlined>
            col
            </v-card>
          </v-col>
        </v-row>

        <v-row dense>
          <v-spacer/>
          <v-col>
            <v-card
            class="pa-3"
            outlined>
            col
            </v-card>
          </v-col>
            <v-col>
            <v-card
            class="pa-3"
            outlined>
            col
            </v-card>
          </v-col>
            <v-col>
            <v-card
            class="pa-3"
            outlined>
            col
            </v-card>
          </v-col>
        </v-row>
        </v-card>
        <v-card class="mt-5 pa-3">
        <v-row dense :style="{height:'120px'}"
        >
          <v-col
          align-self="end">
            <v-card
            class="pa-3"
            outlined>
            col
            </v-card>
          </v-col
          >
            <v-col
            align-self="center">
            <v-card
            class="pa-3"
            outlined>
            col
            </v-card>
          </v-col>
            <v-col
            align-self="start">
            <v-card
            class="pa-3"
            outlined>
            col
            </v-card>
          </v-col>
        </v-row>
      </v-card>
    </v-container>
</template>

<script>
export default {
     name:'GridSystem'
}
</script>

<style>

</style>
