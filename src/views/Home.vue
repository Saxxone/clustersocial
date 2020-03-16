<template>
  <div class="home">
    <MessageComponent />
    running
  </div>
</template>

<script>
import MessageComponent from "@/components/MessageComponent.vue";

export default {
  name: "Home",
  components: {
    MessageComponent
  }
};
</script>
