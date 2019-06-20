<template>
  <v-container fluid>
    <v-layout column align-center>
      <img src="@/assets/logo.png" alt="Vuetify.js" class="mb-5">
    
    </v-layout>
    <v-slide-y-transition mode="out-in">
      <v-layout column>        
        <h1 class="headline">Collaboration Portal</h1>
        <p>Welcome to the Collaboration Portal, bringing you a forum for all of your Q&A's and giving you a feed to stay up to date. </p>

      </v-layout>
    </v-slide-y-transition>
  </v-container>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Component({
  components: {
    HelloWorld,
  },
})
export default class Home extends Vue {}
</script>
