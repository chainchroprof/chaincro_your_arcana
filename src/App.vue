<template>
  <v-app>
    <AppBar/>
    <v-main>
      <HelloWorld/>
      <CheckEntry
         :src="require('./assets/image1.png')"
      />
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import AppBar from './components/AppBar';
import CheckEntry from './components/CheckEntry';

export default {
  name: 'App',

  components: {
    AppBar,
    HelloWorld,
    CheckEntry,
  },

  data: () => ({
    //
  }),
};
</script>
