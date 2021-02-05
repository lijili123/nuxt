<template>
  <div>
    <h3>异步数据</h3>
    <!-- {{info.anme}} -->
  </div>
</template>

<script>
import axios from "axios";
export default {
  name: "",
  asyncData({isDev, route, store, env, params, query, req, res, redirect, error}) {
    // return axios.get("").then((data) => {
    //   return {info: data};
    // });
  },
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
