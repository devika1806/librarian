<template>
    <div class="center">
        <v-row>
            <v-col cols="10" sm="6" offset-sm="3" md="4" offset-md="4" offset="1">
                <v-avatar size="95" tile>
                    <v-img src="@/assets/logo.png"></v-img>
                </v-avatar>
                <h1>Login page</h1>
                <v-text-field label="Username" v-model="username"></v-text-field>
                <v-text-field label="Password" v-model="password" type="password"></v-text-field>
                <v-btn block elevation="2" @click="authenticate()">Login</v-btn>
            </v-col> </v-row>

    </div>
</template>

<script>
export default {
    data() {
        return {
            username: "",
            password: ""
        }

    },
    methods: {
        authenticate() {
            alert("you have loged in")
        }
    },
}
</script>

<style lang="scss" scoped></style>

