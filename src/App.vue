<template>
  <div id="app">
    <MHheader></MHheader>
  </div>
</template>

<script type="text/ecmascript-6">
  import MHheader from 'components/m-header/m-header'

  export default {
    components: {
      MHheader
    }
  }
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "~common/stylus/variable"

  #app
    color: $color-theme
</style>