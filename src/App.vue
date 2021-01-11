<template>
  <v-app>
    <app-bar />
    <v-main>
    </v-main>
  </v-app>
</template>

<script>

import AppBar from './components/core/appBar';

export default {
  name: 'App',

  components: {
    AppBar,
  },

  data: () => ({
    //
  }),
};
</script>
