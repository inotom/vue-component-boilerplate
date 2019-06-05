<template>
  <div class="hello-vue">
    {{ title }}
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'Hello, Vue.js!',
    };
  },
};
</script>

<style lang="scss" scoped>
.hello-vue {
  color: #f00;
}
</style>
