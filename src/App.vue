<script>
import Button from "./components/Button.vue";

export default {
  name: "app",
  components: {
    Button
  }
};
</script>

<template>
  <div>
    <Button
      name='secondaryButton'
      type='solid'
      size='small'
      state='normal'
      ic_start=false
      ic_end=false >
    </Button>
  </div>
</template>

<style scoped>
</style>