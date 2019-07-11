<template>
  <div class="hello-world">
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
.hello-world {
  color: #f00;
}
</style>
