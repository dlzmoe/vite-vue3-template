<template>
  <h1>{{ msg }}</h1>
  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
  </div>
  <p>这是一个基于 vite + vue3 的开发模板。</p>
  <p><a href="https://github.com/dlzmoe/vite-vue3-template">https://github.com/dlzmoe/vite-vue3-template</a></p>
  <p>已经引入 vuex，router，axios，element-plus，less，tailwindcss</p>
</template>

<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
  props: ["msg"],
};
</script>

<style scoped>
.read-the-docs {
  color: #888;
}
p {
  margin-bottom: 1em;
}
</style>
