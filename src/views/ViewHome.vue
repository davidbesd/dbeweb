<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/LogoDbeWeb.png" />
    <Home msg="Wellcome to {dbeWeb} developer page." />
  </div>
</template>

<script>
// @ is an alias to /src
import Home from "@/components/Home.vue";

export default {
  name: "ViewHome",
  components: {
    Home,
  },
};
</script>
