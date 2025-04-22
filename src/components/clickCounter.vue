<template>
  <div>
    <button @click="increase">clicks = {{ count }}</button>
  </div>
</template>

<script>
import counter from "@/mixins/counter";
export default {
  name: "clickCounter",
  mixins: [counter],
};
</script>

<style scoped></style>
