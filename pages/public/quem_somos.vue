<template>
  <div class="container">
    <v-card>
      <v-img :src="require('~/assets/new_school.jpg')" height="100%" class="grey darken-4" />
    </v-card>
    <v-card>
      <v-img :src="require('~/assets/missao.jpg')" height="100%" class="grey darken-4" />
    </v-card>
    <v-card>
      <v-img :src="require('~/assets/aplicativo.jpg')" height="100%" class="grey darken-4" />
    </v-card>
    <v-card>
      <v-img :src="require('~/assets/projeto.jpg')" height="100%" class="grey darken-4" />
    </v-card>
    <v-card>
      <v-img :src="require('~/assets/projeto-1.jpg')" height="100%" class="grey darken-4" />
    </v-card>
    <v-card>
      <v-img :src="require('~/assets/projeto-2.jpg')" height="100%" class="grey darken-4" />
    </v-card>
    <v-card>
      <v-img :src="require('~/assets/equipe.jpg')" height="100%" class="grey darken-4" />
    </v-card>
    <navigation-bar />
  </div>
</template>


<script>
import NavigationBar from "~/components/NavigationBar.vue";

export default {
  components: {
    NavigationBar
  }
}
</script>
<style scoped>

.container{
  overflow-y: auto;
  max-width: 600px
 
}
</style>
