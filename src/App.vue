<template>
  <v-container fluid="fluid">
    <v-row class="mt-4 ml-1 mr-1">
      <v-col xs6>
        <!--<v-card class="primary mt-2">
          <v-card-text>-->
          <div class="ml-5 mt-2">
            <div>
              <div>Membership name</div><strong>Rol user details</strong></div>
          </div>

        <!--  </v-card-text>
        </v-card>-->
      </v-col>
      <v-col xs6>
        <!--<v-card class="primary mt-2">
          <v-card-text>-->
          <div class="ml-5 mt-2">
            <div><v-btn round primary dark>Rounded Button</v-btn><v-btn round primary dark>Rounded Button</v-btn></div>
          </div>

        <!--  </v-card-text>
        </v-card>-->
      </v-col>
      <v-col xs6 v-for="i in 2" :key="i">
        <v-card class="secondary mt-2">
          <v-card-text>6</v-card-text>
        </v-card>
      </v-col>
      <v-col xs4 v-for="i in 3" :key="i">
        <v-card class="primary mt-2">
          <v-card-text>4</v-card-text>
        </v-card>
      </v-col>
      <v-col xs3 v-for="i in 4" :key="i">
        <v-card class="secondary mt-2">
          <v-card-text>3</v-card-text>
        </v-card>
      </v-col>
      <v-col xs2 v-for="i in 6" :key="i">
        <v-card class="primary mt-2">
          <v-card-text>2</v-card-text>
        </v-card>
      </v-col>
      <v-col xs1 v-for="i in 12" :key="i">
        <v-card class="secondary mt-2">
          <v-card-text>1</v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    data () {
      return {
        item: {
          text: 'Get Started'
        },
        nav2: false
      }
    }
  }
</script>

<style lang="stylus">
  @import '../node_modules/vuetify/src/stylus/main'

  @import './css/main.css'
</style>
