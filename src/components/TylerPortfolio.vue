<template>
  <v-container 
    class="grey lighten-5"
    fill-height
    fluid
  >
    <v-row
      class="blue lighten-5"
      style="height: 100%;"
      no-gutters
      ma-0
      pa-0
    >
      <!-- nav column -->
      <v-col
        class="red lighten-1"
        md="3"
        align-self="center"
      >
          <!-- nav items -->
          <v-row>
            <span>test</span>
          </v-row>

          <v-row>
            <span>test</span>
          </v-row>

          <v-row>
            <span>test</span>
          </v-row>

          <v-row>
            <span>test</span>
          </v-row>

      </v-col>


      <!-- body column -->
      <v-col
        class="green lighten-1"
        md="9"
      >
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
    }),
  }
</script>
