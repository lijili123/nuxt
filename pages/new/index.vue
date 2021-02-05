<template>
  <div>
    <div>新闻</div>
    <ul>
      <li>
        <nuxt-link :to="{name: 'detail', query: {id: 'sssss'}}">item1</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/new/123">item2-123</nuxt-link>
      </li>
      <!-- <li>
        <nuxt-link to="/new/dd">item3-456</nuxt-link>
      </li> -->
      <li>
        <nuxt-link :to="{name: 'new-id', params: {id: '789', title: 'this is a new'}}"
          >item3-789动态路由</nuxt-link
        >
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  transition: {
    name: "new",
  },
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
