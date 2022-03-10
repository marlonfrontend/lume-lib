<script>
import { defineComponent } from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { LumeSample } from '@/entry.esm';

export default defineComponent({
  name: 'ServeDev',
  // components: {
  //  LumeSample,
  // }
});
</script>

<template>
  <div id="app">
    <lume-sample />
  </div>
</template>
