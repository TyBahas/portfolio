<template>
  <v-app>
    <v-main>
      <TylerPortfolio/>
    </v-main>
  </v-app>
</template>

<script>
import TylerPortfolio from './components/TylerPortfolio';

export default {
  name: 'App',

  components: {
    TylerPortfolio,
  },

  data: () => ({
    //
  }),
};
</script>
<style>
  html{
    overflow-y:hidden
  }

</style>

