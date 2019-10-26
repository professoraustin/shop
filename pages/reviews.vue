<template>
  <div>
    <app-store-grid :data="services" />
  </div>
</template>

<script>
import { mapGetters } from "vuex";
import AppStoreGrid from "~/components/AppStoreGrid.vue";

export default {
  components: {
    AppStoreGrid
  },
  computed: {
    ...mapGetters(["services"])
  }
};
</script>

<style lang="scss" scoped>
</style>