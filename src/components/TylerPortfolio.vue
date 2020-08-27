<template>
  <v-container 
    class="grey lighten-5 ma-0 pa-0"
    fill-height
    fluid
  >
    <v-row
      id="self-nav-column"
      style="height: 100%;"
      no-gutters
    >
      <!-- nav column -->
      <v-col
        md="2"
        align-self="center"
      >
          <!-- nav items -->
          <v-row
          class="ma-1 pa-5"
          align="center"
          justify="center"
          >
            <v-img
              id="self-rounded-card"
              :src="require('../assets/logo.svg')"
              class="my-1"
            />
          </v-row>

          <v-row
          class="ma-1 pa-1"
          align="center"
          justify="center"
          >
            <span
              id="self-nav-link"
            >
              About
            </span>
          </v-row>

          <v-row
          class="ma-1 pa-1"
          align="center"
          justify="center"
          >
            <span
              id="self-nav-link"
            >
              Experience
            </span>
          </v-row>

          <v-row
          id="row"
          class="ma-1 pa-1"
          align="center"
          justify="center"
          >
            <span
              id="self-nav-link"
            >
              Skills
            </span>
          </v-row>

      </v-col>


      <!-- body column -->
      <v-col
        class="green lighten-1"
        md="10"
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
<style>
#self-rounded-card {
  border-radius: 50%; 
  border: 0.5rem solid rgba(255, 255, 255, 0.2);
  max-height: 150px;
  max-width: 150px;
}

#self-nav-column{
  background-color: #bd5d38;
}

#self-nav-link{
  font-weight: 800;
  letter-spacing: 0.05rem;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 0.5);
}
</style>
