<template>
  <v-content>
    <section><motto /></section>
    <section><rice-details /></section>
    <section><how-to-make /></section>
    <section><contact /></section>
  </v-content>
</template>

<script>
import Motto from "~/components/Motto.vue";
import RiceDetails from "~/components/RiceDetails.vue";
import HowToMake from "~/components/HowToMake.vue";
import Contact from "~/components/Contact.vue";

export default {
  components: {
    Motto,
    RiceDetails,
    HowToMake,
    Contact
  }
};
</script>
