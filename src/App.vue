<template>
  <v-app>
    <div class='bg'>
        <v-container
        fill-height
        ma-1
        pa-4
        >
        <v-row
        align='center'
        justify='center'
        >
        <v-col
        align='center'
        justify='center'
        >
          <v-img
            src='./assets/logo.png'
            max-width='192px'
            max-height='192px'
            class='ma-4'
            >
            </v-img>
          <div class='white--text display-2 ma-3'>
            New Site Launching 13/07/2020
          </div>
        </v-col>
        </v-row>
        </v-container>
    </div>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  components: {
  },

  data: () => ({
    //
  }),
};
</script>
<style>
  .bg {
    width: 100%;
    height: 100%;
    background:
      url('./assets/profile-bg.jpg')
      no-repeat
      center
      center;
    background-size: cover;
    transform: scale(1.0);
  }
</style>
