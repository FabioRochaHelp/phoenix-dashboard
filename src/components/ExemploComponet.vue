<template>
  <h1>Exemple</h1>
</template>

<script>

export default defineComponent({
  name: 'ExampleComponent',
  props: {
    title: {
      type: String,
      required: true,
    },
  },
});
</script>
