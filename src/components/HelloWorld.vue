<!-- HelloWorld.vue -->
<template>
  <div>
    <slot> ... </slot>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: ['b'],
  mounted() {
    console.log(this.b().focus());
  },
};
</script>
