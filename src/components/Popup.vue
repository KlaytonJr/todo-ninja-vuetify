<template>
    <div class="text-center">
        <v-dialog v-model="dialog" width="600px">
        <template v-slot:activator="{ on }">
            <v-btn class="success" v-on="on">Add New Project</v-btn>
        </template>
        <v-card>
            <v-card-title class="headline grey lighten-2" primary-title>Add a New Project</v-card-title>
        </v-card>
        </v-dialog>
    </div>
</template>

<script>
export default {
    name: "Popup"
}
</script>