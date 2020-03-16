<template>
  <b-row>
    <b-form>
      <b-form-input v-model="text"> </b-form-input>
    </b-form>
  </b-row>
</template>

<script>
export default {
  name: "TextInputComponent",
  props: {},
  data() {
    return {
      text: ""
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
