<template>
  <div>
     {{text}}
  </div>
</template>
<script>
  const prefixCls = 'vm-example';
  export default {
    name: 'example',
    data() {
      return {
        text: 'example text'
      }
    }
  }
</script>
<style lang="less">
  @examplePrefixCls: vm-example;
</style>
