<template>

  <v-content pt-5>
    <v-container fill-height>
      <v-layout justify-center align-center wrap>
        <v-flex xs12 mb-5>
          <v-container grid-list-x1 pa-0>
            <v-layout row wrap justify-center>
              <v-flex xs12 sm6 md4 d-flex pa-2>
                <v-card flat>
                  <v-img height="200" :src="require('../assets/blueprint.jpg')"></v-img>
                  <v-card-title class="headline">headline</v-card-title>
                  <v-card-text>Every achievement begins with a vision. It is built on a foundation of creative concepts and dreams to become something bigger and better. At AlphaConstruction we build with those who follow a vision, not a path.</v-card-text>
                </v-card>
              </v-flex>
              <v-flex xs12 sm6 md4 d-flex pa-2>
                <v-card flat>
                  <v-img height="200" :src="require('../assets/construction.jpg')"></v-img>
                  <v-card-title class="headline">headline</v-card-title>
                  <v-card-text>Every achievement begins with a vision. It is built on a foundation of creative concepts and dreams to become something bigger and better. At AlphaConstruction we build with those who follow a vision, not a path.</v-card-text>
                </v-card>
              </v-flex>
              <v-flex xs12 sm6 md4 d-flex pa-2>
                <v-card flat>
                  <v-img height="200" :src="require('../assets/architecture.jpg')"></v-img>
                  <v-card-title class="headline">headline</v-card-title>
                  <v-card-text>Every achievement begins with a vision. It is built on a foundation of creative concepts and dreams to become something bigger and better. At AlphaConstruction we build with those who follow a vision, not a path.</v-card-text>
                </v-card>
              </v-flex>
            </v-layout>
          </v-container>
        </v-flex>
      </v-layout>
    </v-container>
  </v-content>

</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
  components: {
    
  },
})
export default class Home extends Vue {}
</script>
