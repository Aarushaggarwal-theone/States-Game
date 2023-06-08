<template>
  <main>
  <NavBar/>

  </main>
</template>

<script lang="ts">
import Vue from 'vue'
import NavBar from '~/components/NavBar.vue';

export default Vue.extend({
    name: "IndexPage",
    components: { NavBar }
})
</script>
