<template>
  <div class="app">
    
  </div>
</template>

<script lang="ts">
import { defineComponent, reactive, toRefs, ref } from 'vue';

export default defineComponent({
  name: 'App',
  components: {},
  setup() {
    const name = ref<string>('Link')
    const age = ref<number | string>(25)

    return { name, age }
  }
});
</script>

<style>

</style>
