<template>
  <div id="app">
    <v-app>
      <v-main>
        <v-toolbar>
          <v-toolbar-title>Formularium <b>α</b></v-toolbar-title>
          <v-spacer></v-spacer>
        </v-toolbar>
        <router-view />
      </v-main>
    </v-app>
  </div>
</template>
<script>
export default {
  name: "app",
  components: {}
};
</script>

<style lang="scss"></style>
