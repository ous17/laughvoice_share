<template>
  <div>
    <h1>{{ message }}</h1>
     <input type="file" class="form-control-file" id="inputFile">
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
      message: "`o-zz",
    };
  },
  methods: {
    openExploler: function () {
      window.open("C:\Users\r_fsa");
    },
  },
};
</script>
