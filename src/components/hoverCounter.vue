<template>
  <div>
    <button @mouseover="increase">clicks = {{ count }}</button>
  </div>
</template>

<script>
import counter from "@/mixins/counter";
export default {
  name: "hoverCounter",
  mixins: [counter],
};
</script>

<style scoped></style>
