<template>
  <v-app>
    <v-app-bar
      color="blue"
      dark
      app
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-toolbar-title class="headline">
        <span>aoisensi.info</span>
      </v-toolbar-title>
    </v-app-bar>

    <v-content>
      <Index/>
    </v-content>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue';
import Index from './components/Index.vue';

export default Vue.extend({
  name: 'App',
  components: {
    Index,
  },
  data: () => ({
    //
  }),
});
</script>
