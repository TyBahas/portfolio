<template>
  <v-container 
    class="ma-0 pa-0"
    fill-height
    fluid
    id="self-nav-column"
    
  >
    <v-row
      style="height: 100%;"
      no-gutters
    >
      <!-- nav column -->
      <v-col
        md="2"
        id="self-nav-column"
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
          align="center"
          justify="center"
          id="self-nav-link"
          >
            <ul 
            class="ma-1 pa-1"
            align="center"
            justify="center"
            >
              <li class="ma-1 pa-1">About</li>
              <li class="ma-1 pa-1">Experience</li>
              <li class="ma-1 pa-1">Skills</li>
            </ul>
          </v-row>
      </v-col>


      <!-- body column -->
      <v-col
        class="white"
        md="10"
      >
      <div 
      id="self-content" 
      class="ma-4 pa-1" 
      >
        <section id="about"  class="self-resume-section">
          <p>about</p>
        </section>

        <hr>
        
        <section id="experience" class="self-resume-section">
          <p>experience</p>
        </section>

        <hr>

        <section id="skills"  class="self-resume-section">
          <p>skills</p>
        </section>

      </div>

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
li{
  list-style-type: none;
  padding-left: 0;
  letter-spacing: 0.05rem;
}
#self-content{
  background-color: blue;
  overflow-y: scroll;
  height: 95vh;
}

.self-resume-section{
  padding-left: 3rem;
  padding-right: 3rem;
  padding-top: 5rem;
  padding-bottom: 5rem;
  height: 100vh;
  
}
</style>
