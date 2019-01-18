<template>
  <div class="container-fluid no-gutters main" style="overflow-x:hidden;background-color: #FFF3E0;">
    <d2header/>
  </div>
</template>

<script>
import d2header from "./components/d2header/DhisHeader";

export default {
  name: "App",
  components: {
    d2header,
  }
};
</script>
<style lang="scss">
  @import 'assets/scss/style';
</style>