<template>
  <div class="header">
   <div class="header-left">
   <div class="iconfont back-icon">&#xe624;</div>
   </div>
   <div class="header-input">
   <span class="iconfont">&#xe632;</span>
   输入城市/景点/主题
   </div>
   <div class="header-right">
   城市
   <span class="iconfont arrow-icon">&#xe64a;</span>
   </div>
  </div>
</template>
<script>
export default {
  name: 'HomeHeader'
}
</script>
<style lang="stylus" scoped>
@import '~styles/varibles.styl'
.header
  height:.86rem
  display:flex
  background:$bgColor
  color:#fff
  align-items:center
  .header-left
    width:.64rem
    .back-icon
      text-align:center
      font-size:.4rem
  .header-input
    flex:1
    background:#fff
    border-radius:.1rem
    height:.64rem
    line-height:.64rem
    margin-left:.2rem
    padding-left:.2rem
    color:#ccc
  .header-right
    min-width: 1.04rem
    padding: 0 .1rem
    float: right
    text-align: center
    color: #fff
    .arrow-icon
      font-size:.24rem
</style>
