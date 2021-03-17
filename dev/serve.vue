<script>
import { defineComponent } from 'vue';
import { UkitSample } from '@/entry.esm';

export default defineComponent({
  name: 'ServeDev',
  components: {
   UkitSample,
  }
});
</script>

<template>
  <div id="app">
    <ukit-sample />
  </div>
</template>
