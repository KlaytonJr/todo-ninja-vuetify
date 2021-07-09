<template>
  <div class="dashboard">
    <h1 class="subtitle-1 grey--text">Dashboard</h1>
    
    <!-- v-container stay centralized -->
    <v-container fluid class="my-5">
      
      <v-card flat class="px-3">
        <v-row row wrap class="pa-3">
          <v-col xs="12" md="6">
            <div class="caption grey--text">Project title</div>
            <div>Create a new website</div>
          </v-col>
          <v-col xs="6" sm="4" md="2">
            <div class="caption grey--text">Person</div>
            <div>The Net Ninja</div>
          </v-col>
          <v-col xs="6" sm="4" md="2">
            <div class="caption grey--text">Due by</div>
            <div>1st Jan 2019</div>
          </v-col>
          <v-col xs="2" sm="4" md="2">
            <div class="caption grey--text">Status</div>
            <div>ongoing</div>
          </v-col>
        </v-row>
      </v-card>

    </v-container>
  </div>
</template>

<script>
  export default {
    name: 'Dashboard',
  }
</script>
