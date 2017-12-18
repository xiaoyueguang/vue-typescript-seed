<template lang='pug'>
  header(@click = 'onClick') {{msg}}
</template>

<script lang='ts'>
  import Vue from 'vue'
  import Component from 'vue-class-component' 

  @Component
  export default class XHeader extends Vue {
    msg: string = 'Hello World'
    onClick (): void {
      alert(this.msg)
    }
  }
</script>

<style>

</style>
