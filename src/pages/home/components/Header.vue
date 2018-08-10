<template>
<div class="header">
    <div class="header-left">
    <div class="iconfont back-icon">&#xe624;</div>
    </div>
    <div class="header-input">
    <span class="iconfont">&#xe632;</span>
    输入城市/景色/游玩</div>
    <div class="header-right">城市
    <span class="iconfont">&#xe6aa;</span>
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
        display: flex
        line-height: 43px
        background: $bgcolor
        color:#fff
        .header-left
            width: 48px
            float: left
            .back-icon
                text-align: center
        .header-input
             flex:1
             margin-top:5px
             height:32px
             line-height:32px
             padding-left:7px
             margin-left:.12rem
             background:#fff
             border-radius:5px
             color:#ccc
        .header-right
            width:80px
            float:right
            text-align:center

</style>
