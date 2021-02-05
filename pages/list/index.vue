<template>
  <div>
    <div>列表</div>
    <ul>
      <li>
        <nuxt-link :to="{name: 'detail', query: {id: 'sssss'}}">item1</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/new">item2</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/list">item3</nuxt-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "",
  data() {
    return {};
  },
  components: {},
  created() {},
  mounted() {},
  methods: {},
};
</script>
<style scoped></style>
