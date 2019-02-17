<template>
  <section>
    <input type="text" v-model="text">
    <div>
      Input Text: <span v-text="text" class="input-text"></span>
    </div>
  </section>
</template>

<script lang="ts">
export default {
  data() {
    return {
      text: ""
    }
  }
};
</script>

<style scoped>
.input-text {
  background-color: red;
};
</style>
