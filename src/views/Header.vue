<template>
  <div>
    <v-app-bar text dense dark fixed class="align-content-center">
      <v-img src="../assets/logo.png" max-height="30" max-width="30" pr-2></v-img>
      <span style="fontSize: 25px; marginLeft: 5px; fontFamily: fantacy" to="/">Young Democrat Movement</span>
      <v-spacer></v-spacer>
      <router-link to="/register">Do you want to be a member?</router-link>
    </v-app-bar>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

