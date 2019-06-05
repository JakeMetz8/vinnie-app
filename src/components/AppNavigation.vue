<template>
  <v-toolbar app color="teal" dark>
    <v-toolbar-side-icon
      class="hidden-sm-and-up"
      @click="drawer = !drawer"
    ></v-toolbar-side-icon>
    <v-spacer class="hidden-sm-and-up"></v-spacer>
    <v-toolbar-title>{{ appTitle }}</v-toolbar-title>
    <v-spacer class="hidden-xs-only"></v-spacer>
    <v-btn class="hidden-xs-only" flat>SIGN IN</v-btn>
  </v-toolbar>
</template>
<script>
export default {
  name: 'AppNavigation',
  data() {
    return {
      appTitle: 'Vinnie App'
    };
  }
};
</script>
<style scoped></style>
