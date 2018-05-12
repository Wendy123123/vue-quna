<template>
  <div class="home-header">
      <div class="header-left">
          <span class="iconfont icon-qrcode">&#xe61a;</span>
      </div>
      <div class="header-search">
          <span class="iconfont icon-search">&#xe622;</span>
          <input type="text" value='搜索'>
      </div>
      <div class="header-right">
          <span>城市</span>
          <span class="iconfont">&#xe64a;</span>
      </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" scoped>
@import '~styles/varibles.styl';
.home-header
    display: flex
    line-height: .9rem
    padding-top: .12rem
    .icon-qrcode
        font-size .6rem
    .header-left
        float: left
        width: .8rem
        text-align center
        font-size .3rem
    .header-right
        width: 1.4rem
        float: right
        text-align: center
        color: #2e2e2e
        font-size: .28rem
    .header-search
        position: relative
        flex: 1
        input
            box-sizing: border-box
            background: $header-input-bg-color
            border-radius: 50px
            width: 100%
            line-height: .78rem
            font-size: .28rem
            color: #afafaf
            padding-left: .76rem
            padding-right: .66rem
        .icon-search
            position: absolute
            left .3rem
</style>
