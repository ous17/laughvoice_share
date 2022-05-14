<template>
  <div>
    <h1>{{ message }}</h1>
    <b-button v-on:click="openExploler" variant="outline-info"
      >ファイルを開く</b-button
    >
  </div>
</template>
<style>
h1 {
  font-size: 19px;
}
</style>
<script>
import BootstrapVue from "bootstrap-vue";
export default {
  data() {
    return {
      message: "`o-ai",
    };
  },
  methods: {
    openExploler: function () {
      window.open("C:\Users\r_fsa");
    },
  },
};
</script>
