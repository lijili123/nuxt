<template>
  <div>
    <p v-if="error.statusCode == 404">404</p>
    <p v-else>500</p>
  </div>
</template>

<script>
export default {
  name: "",
  props: ["error"],
  data() {
    return {};
  },
  components: {},
  methods: {},
  created() {},
  mounted() {},
};
</script>
<style scoped></style>
