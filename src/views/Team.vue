<template>
  <div class="team">
    <HelloWorld msg="Team" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Team",
  components: {
    HelloWorld
  }
};
</script>
