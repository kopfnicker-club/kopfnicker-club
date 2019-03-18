<template>
  <div class="kasse">
    <HelloWorld msg="Kasse" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Kasse",
  components: {
    HelloWorld
  }
};
</script>
