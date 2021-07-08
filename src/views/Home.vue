<template>
  <div class="home">
    <h1>Homepage</h1>
    
    <v-btn class="pink white--text">Click me</v-btn>

    <v-btn dark color="pink">Click me</v-btn>

    <v-btn depressed color="pink">Click me</v-btn> 
    <!-- Remove the box-shadow -->

    <v-btn flat>Click me</v-btn>
    <!-- Background transparent -->

    <!-- ICONS -->
    <v-btn depressed class="pink white--text">
      <v-icon left>mdi-email</v-icon>
      <span>email me</span>
    </v-btn>

    <v-btn depressed small class="pink white--text">
      <v-icon left small>mdi-email</v-icon>
      <span>email me</span>
    </v-btn>

    <v-btn depressed large class="pink white--text">
      <span>email me</span>
      <v-icon large class="pl-4">mdi-email</v-icon>
    </v-btn>

    <v-btn depressed small dark color="purple">
      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn fab depressed small dark color="purple">
      <v-icon>mdi-heart</v-icon>
    </v-btn>

  </div>
</template>

<script>
  export default {
    name: 'Home',
  }
</script>
