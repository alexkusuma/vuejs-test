<script>
import Vue from 'vue';
import VuejsTest from '@/vuejs-test.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VuejsTest
  }
});
</script>

<template>
  <div id="app">
    <vuejs-test />
  </div>
</template>
