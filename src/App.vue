<template lang='pug'>
  #app
    x-header
    router-view
</template>

<script lang="ts">
  import Vue from 'vue'
  import Component from 'vue-class-component' 
  import XHeader from '@/components/XHeader.vue'

  @Component({
    name: 'App',
    components: {
      XHeader
    }
  })
  export default class App extends Vue {
  }
</script>

<style>

</style>
