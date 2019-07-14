<template>
  <div class="hello-world">
    {{ title }}
  </div>
</template>

<script>
import Vue from 'vue';

export default Vue.extend({
  data() {
    return {
      title: 'Hello, Vue.js!',
    };
  },
});
</script>

<style lang="scss" scoped>
.hello-world {
  color: #f00;
}
</style>
