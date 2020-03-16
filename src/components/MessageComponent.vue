<template>
  <b-row>
    <b-card>
      <b-card-body>
        {{ message }}
      </b-card-body>
    </b-card>
  </b-row>
</template>

<script>
export default {
  name: "MessageComponent",
  props: {
    // message
  },
  data() {
    return {
      message: "Welcome to Cluster Social"
    };
  }
};
</script>

<style scoped lang="scss"></style>
