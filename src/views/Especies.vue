<template>
  <cards-section></cards-section>
</template>
<script>
import CardsSection from "../components/CardsSection.vue";
export default {
  name: "Especies",
  data: () => ({
    items: [],
  }),

  components: {
    CardsSection,
  },
};
</script>
