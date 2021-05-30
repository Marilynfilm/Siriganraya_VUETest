<template>
  <myname></myname>
  <myability></myability>
</template>

<script>
import myname from "./components/myname.vue";
import myability from "./components/myability.vue";
export default {
  name: "App",
  components: {
    myname: myname,
    myability: myability,
  },
};
</script>

<style scoped>
* {
  background-color: blanchedalmond;
}
</style>