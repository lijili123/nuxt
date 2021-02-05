<template>
  <div>{{ $route.params.id }}</div>
</template>

<script>
export default {
  validate({params}) {
    return /^\d+$/.test(params.id);
  },
  data() {
    return {
      title: this.$route.params.title,
    };
  },
  head() {
    return {
      title: this.title,
      meta: [
        {
          hid: "descirption",
          name: "news",
          content: "this is new page",
        },
      ],
    };
  },
  components: {},
  created() {},
  mounted() {
    console.log(this.title);
  },
  methods: {},
};
</script>
<style scoped></style>
