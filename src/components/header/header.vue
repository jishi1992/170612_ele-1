<template>
  <div class="header">
    <div class="content-wrapper">
      <div class="avatar">
        <img src="http://static.galileo.xiaojukeji.com/static/tms/seller_avatar_256px.jpg" >
      </div>
      <div class="content">
        <div class="title">
          <span class="brand"></span>
          <span class="name">粥品香坊（回龙观）</span>
        </div>
        <div class="description">蜂鸟专送/38分钟送达</div>
        <div class="supports">
          <span class="icon special"></span>
          <span class="text">在线支付满28送晓飞张写真两套</span>
        </div>
        <div class="supports-count">
          <span class="count">5个</span>
          <span class="icon-keyboard_arrow_right"></span>
        </div>
      </div>
    </div>
    <div class="bulletin-wrapper">
      <span class="bulletin-title"></span>
      <span class="bulletin-text">粥品香坊其烹饪粥料的秘方源于中国千年古法，在融和现代制作工艺，由世界烹饪大师屈浩先生领衔研发。坚守纯天然、0添加的良心品质深得消费者青睐，发展至今成为粥类的引领品牌。是2008年奥运会和2013年园博会指定餐饮服务商。</span>
      <span class="icon-keyboard_arrow_right"></span>
    </div>
    <div class="bg">
      <img src="http://static.galileo.xiaojukeji.com/static/tms/seller_avatar_256px.jpg" width="100%" height="100%">
    </div>
    <div class="mask">
      <div class="mask-wrapper">
        <div class="mask-main">
          <h1>晓飞猪蹄（西部硅谷）</h1>
          <div class="stars-wrapper">
            <div class="stars star-48">
              <span class="star on"></span>
              <span class="star on"></span>
              <span class="star on"></span>
              <span class="star half"></span>
              <span class="star off"></span>
            </div>
          </div>
          <div class="info">
            <div class="line"></div>
            <div class="text">优惠信息</div>
            <div class="line"></div>
          </div>
          <ul class="list">
            <li>
              <span class="iocn special"></span>
              <span>在线支付满28送晓飞张写真</span>
            </li>
            <li>
              <span class="iocn decrease"></span>
              <span>晓飞张写真全场8折</span>
            </li>
            <li>
              <span class="iocn discount"></span>
              <span>晓飞张单人精彩套餐</span>
            </li>
            <li>
              <span class="iocn guarantee"></span>
              <span>该商家支持发票,请下单写好发票抬头</span>
            </li>
            <li>
              <span class="iocn invoice"></span>
              <span>已加入“晓飞张上门服务”计划,食品安全保障</span>
            </li>
          </ul>
          <div class="info">
            <div class="line"></div>
            <div class="text">商家公告</div>
            <div class="line"></div>
          </div>
          <div class="context">
            <p class="text">
              粥品香坊其烹饪粥料的秘方源于中国千年古法，在融和现代制作工艺，由世界烹饪大师屈浩先生领衔研发。坚守纯天然、0添加的良心品质深得消费者青睐，发展至今成为粥类的引领品牌。是2008年奥运会和2013年园博会指定餐饮服务商。
            </p>
          </div>
        </div>
      </div>
      <div class="mask-footer">
        <span class="icon-close"></span>
      </div>
    </div>
  </div>
</template>

<script>
  export default {}
</script>

<style lang="stylus" rel="stylesheet/stylus">
  @import "../../common/stylus/mixin.styl"
  .header
    position relative
    background rgba(7,17,27,.5)
    overflow hidden
    .content-wrapper
      position relative
      margin 24px 12px 18px 24px
      font-size 0
      .avatar
        display inline-block
        vertical-align top
        img
          border-radius 2px
          width 64px
          height 64px
      .content
        margin-left 16px
        display inline-block
        .title
          margin 2px 0 8px 0
          .brand
            vertical-align top
            display inline-block
            width 30px
            height 18px
            background-repeat no-repeat
            background-size 100% 100%
            bg-image(brand)
          .name
            margin-left 6px
            font-size 16px
            color rgb(255,255,255)
            font-weight bold
            line-height 18px


        .description
          font-size 12px
          line-height 12px
          color rgb(255,255,255)
          font-weight 200
        .supports
          margin 10px 0 2px 0
          .icon
            vertical-align top
            display inline-block
            width 12px
            height 12px
            background-repeat no-repeat
            background-size 100% 100%
            &.decrease
              bg-image(decrease_1)
            &.discount
              bg-image(discount_1)
            &.guarantee
              bg-image(guarantee_1)
            &.invoice
              bg-image(invoice_1)
            &.special
              bg-image(special_1)
          .text
            margin-left 4px
            font-size 10px
            color rgb(255,255,255)
            font-weight 200px
            line-height 12px
        .supports-count
          position absolute
          right 0
          bottom 0
          background rgba(0,0,0,0.2)
          width 48px
          height 24px
          text-align center
          border-radius 8px
          .count
            line-height 24px
            font-size 10px
            color rgb(255,255,255)
            font-weight 200
          .icon-keyboard_arrow_right
            line-height 24px
            font-size 10px
            color rgb(255,255,255)
            font-weight 200

    .bulletin-wrapper
      position relative
      height 28px
      line-height 28px
      font-size 10px
      color rgb(255,255,255)
      font-weight 200
      padding 0 21px 0 12px
      white-space nowrap
      overflow hidden
      text-overflow ellipsis
      background rgba(7,17,27,0.2)
      .bulletin-title
        margin-right  4px
        margin-top: 8px
        vertical-align top
        display inline-block
        width 22px
        height 12px
        background-repeat no-repeat
        background-size 100% 100%
        bg-image(bulletin)
      .icon-keyboard_arrow_right
        position absolute
        right 12px
        line-height 28px


    .bg
      z-index -1
      position absolute
      left 0
      top 0
      right 0
      bottom 0
      filter blur(10px)
    .mask
      position fixed
      z-index 99
      left 0
      top 0
      width 100%
      height 100%
      background rgba(7,17,27,0.8)
      overflow auto
      .mask-wrapper
        clearfix()
        min-height 100%
        .mask-main
          overflow hidden
          padding-bottom 64px
          h1
            text-align center
            font-size 16px
            color rgb(255,255,255)
            font-weight 700
            line-height 16px
            margin-top 64px
          .stars-wrapper
            height 24px
            margin 16px 0 28px 0
            text-align center
            .stars
              .star
                display inline-block
                background-repeat no-repeat
                background-size 100% 100%
              &.star-48
                .star
                  width 20px
                  height 19px
                  margin-right 20px
                  &:last-child
                    margin-right 0
                  &.on
                    bg-image("../star/star48_on")
                  &.half
                    bg-image("../star/star48_half")
                  &.off
                    bg-image("../star/star48_off")
              &.star-36
                .star
                  width 15px
                  height 14px
                  margin-right 15px
                  &:last-child
                    margin-right 0
                  &.on
                    bg-image("../star/star36_on")
                  &.half
                    bg-image("../star/star36_half")
                  &.off
                    bg-image("../star/star36_off")
              &.star-24
                .star
                  width 10px
                  height 10px
                  margin-right 10px
                  &:last-child
                    margin-right 0
                  &.on
                    bg-image("../star/star24_on")
                  &.half
                    bg-image("../star/star24_half")
                  &.off
                    bg-image("../star/star24_off")
          .info
            width 80%
            margin 0 auto
            font-size 14px
            color rgb(255,255,255)
            display flex
            align-items center
            .line
              flex 1
              width 0
              height 2px
              background rgba(255,255,255,0.2)
            .text
              margin 0 12px

          .list
            margin 24px auto 28px auto
            width 80%
            font-size 12px
            line-height 12px
            font-weight 200
            color rgb(255,255,255)
            li
              margin-bottom 12px
              margin-left 6px
              &:last-child
                margin-bottom 0
              .iocn
                vertical-align middle
                display inline-block
                background-size 100% 100%
                background-repeat no-repeat
                width 16px
                height 16px
                &.decrease
                  bg-image(decrease_2)
                &.discount
                  bg-image(discount_2)
                &.guarantee
                  bg-image(guarantee_2)
                &.invoice
                  bg-image(invoice_2)
                &.special
                  bg-image(special_2)

          .context
            width 80%
            margin 24px auto 0 auto
            .text
              padding 0 12px
              font-size 12px
              line-height 24px
              font-weight 200
              color rgb(255,255,255)

      .mask-footer
        text-align center
        font-size 32px
        color rgba(255,255,255,.5)
        margin-top -64px
</style>
