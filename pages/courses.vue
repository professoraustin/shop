<template>
  <div>
    <app-store-grid :data="courses" />
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
    ...mapGetters(["courses"])
  }
};
</script>

<style lang="scss" scoped>
</style>