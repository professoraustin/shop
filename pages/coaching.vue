<template>
  <div>
    <app-store-grid :data="coaching" />
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
    ...mapGetters(["coaching"])
  }
};
</script>

<style lang="scss" scoped>
</style>