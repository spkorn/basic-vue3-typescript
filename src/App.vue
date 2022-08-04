<template>
  <div>
    <h1>App.vue</h1>
    <span>#Count1: {{ count1 }}</span> <br />
    <span>#Count2: {{ count2 }}</span> <br />
  </div>
</template>

<script lang="ts">
import { defineComponent, ref } from "vue";

export default defineComponent({
  setup() {
    let count1 = 11;
    const count2 = ref<number>(0);

    return {
      count1,
      count2,
    };
  },
});
</script>
