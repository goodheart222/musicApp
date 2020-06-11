<template>
  <div class="m-header">
    <div class="icon"></div>
    <div class="text">Chicken Music</div>
  </div>
</template>

<script>
export default {
  name: 'MHeader'
}
</script>

<style lang="stylus" scoped>
  @import '~common/stylus/variable'
  @import '~common/stylus/mixin'
  .m-header
    position:relative
    height:44px
    text-align :center
    color:$color-theme
    font-size :0
    .icon
      display:inline-block
      bg-image('logo')
      width:30px
      height:32px
      background-size:30px 32px
      vertical-align :top
      margin-top :3px
      margin-right :3px
    .text
      display:inline-block
      line-height :44px
      font-size :$font-size-large
</style>
