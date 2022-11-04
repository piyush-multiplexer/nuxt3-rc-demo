<template>
  <div>
    <div>Hello World</div>
    <div>Calc {{ total }}</div>
  </div>
</template>
<script lang="ts">
export default defineComponent({
  setup() {
    const num1 = ref(1);
    const num2 = ref(1);
    const total = num1.value + num2.value;

    return { total };
  },
});
</script>
