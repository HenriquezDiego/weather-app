<template>
  <v-container fluid class="fill-height pt-0 pb-0">
    <v-row class="fill-height">
      <v-col class="primary" md="3" sm="12"
        ><v-row class="sidebar"> </v-row>
      </v-col>
      <v-col class="secondary" xs="12"></v-col> </v-row
  ></v-container>
</template>

<script>
export default {
  name: "Home",

  components: {},
};
</script>

<style scoped>
.sidebar {
  background-image: url("@/assets/img/Cloud-background.png");
  background-position: 45% 20%;
  background-size: initial;
  height: 50%;
  filter: grayscale(200%) opacity(0.1) drop-shadow(0 0 0 black) !important;
}
</style>
