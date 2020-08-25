<template>
  <div id="app" class="container p-2">
		<demo-ref></demo-ref>
		
  </div>
</template>

<script>
import demoRef from '@/components/ref-parent-children/demo.vue';
export default {
  name: 'App',
	components: { demoRef }
}
</script>

<style>
</style>
