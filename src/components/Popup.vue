<template>
    <div class="text-center">
        <v-dialog v-model="dialog" width="600px">
            <template v-slot:activator="{ on }">
                <v-btn class="success" v-on="on">Add New Project</v-btn>
            </template>
            <v-card>
                <v-card-title class="headline grey lighten-4" primary-title>Add a New Project</v-card-title>
                <v-card-text>
                    <v-form class="px-3">
                        <v-text-field label="Title" v-model="title" prepend-icon="mdi-folder"></v-text-field>
                        <v-textarea label="Information" v-model="content" prepend-icon="mdi-pencil"></v-textarea>
                        <v-btn plain class="sucsess mx-0 mt-3" @click="submit">Add project</v-btn>
                    </v-form>
                </v-card-text>
            </v-card>
        </v-dialog>
    </div>
</template>

<script>
export default {
    name: "Popup",

    data() {
        return {
            title: '',
            content: ''
        }
    },

    methods: {
        submit() {
            console.log(this.title, this.content);
        }
    }
}
</script>