<template lang="fr">
  <div>
    <v-app-bar color="#580000"  elevate-on-scroll scroll-target="#scrolling-techniques-7">
      <v-tabs
      background-color="transparent"
      color="white"
      fixed-tabs
    >
      <v-tab
        v-for="item in items"
        :key="item"
      >
        {{ item }}
      </v-tab>
    </v-tabs>
    </v-app-bar>
  </div>
</template>
<script>
export default {
  name: "Navbar",
  data: function () {
    return {
      items: ["Accueil","Qui Suis-je","Réalisations","Contact"]
    }
  }
};
</script>
<style scoped lang="scss"></style>
