<template>
  <div class="detail_header">
    <div class="bar">
      <span class="homeIcon" @click="$router.replace('/home')"></span>
      <span class="logo"></span>
      <div class="right">
        <span class="search" @click="$router.replace('/home')"></span>
        <span class="shopCart" @click="$router.replace('/shopcart')"></span>
      </div>
    </div>
  </div>
</template>

<script>
  export default {}
</script>

<style lang="stylus" rel="stylesheet/stylus" scoped>
  .detail_header
    position fixed
    z-index 66
    width 100%
    top 0
    left 0
    background-color #fafafa
    height 44px
    box-sizing border-box
    padding 0 12px
    border-bottom 1px solid lightgrey
  .bar
    position relative
    width 100%
    height 44px
    .homeIcon
      margin-top 4px
      display inline-block
      padding-top 4px
      margin-left 6px
      width 23px
      height 28px
      vertical-align middle
      background-image url("//yanxuan-static.nosdn.127.net/hxm/yanxuan-wap/p/20161201/style/img/sprites/hd-s342878591a-9af1a97852.png");
      background-repeat no-repeat
      background-position: 0 -37px;
      background-size 85px 222px
    .logo
      position: absolute
      top: 0
      right: 0
      bottom: 0
      left: 0
      margin: auto
      width: 86px
      height: 28px
      background-position: 0 -64px;
      display: inline-block;
      vertical-align: middle;
      background-image: url(//yanxuan-static.nosdn.127.net/hxm/yanxuan-wap/p/20161201/style/img/sprites/hd-s342878591a-9af1a97852.png);
      background-repeat: no-repeat;
      background-size: 86px 199px;
      padding-top -6px
    .right
      width: 20%;
      position absolute
      top 12px
      right 0
      margin-left: auto;
      margin-right: 5px;
      margin-top: -7px;
      .search
        position: relative;
        bottom: 0;
        width: 32px;
        height: 32px;
        background-position: 0 -166px;
        display: inline-block;
        vertical-align: middle;
        background-image: url(//yanxuan-static.nosdn.127.net/hxm/yanxuan-wap/p/20161201/style/img/sprites/hd-s342878591a-9af1a97852.png);
        background-repeat: no-repeat;
        background-size: 86px 200px;
      .shopCart
        position: relative;
        width: 32px;
        height: 32px;
        background-position: 0 0;
        display: inline-block;
        vertical-align: middle;
        background-image: url(//yanxuan-static.nosdn.127.net/hxm/yanxuan-wap/p/20161201/style/img/sprites/hd-s342878591a-9af1a97852.png);
        background-repeat: no-repeat;
        background-size: 86px 200px;

</style>
