<template>
  <div>
    <div class="top">
      <a class="back" @click="$router.back()">
        <i class="iconfont icon-zuojiantou"></i>
      </a>
      <span>支付订单</span>
    </div>
    <div class="mid">
      <div class="pay">
        <img
          class="img1"
          src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fwww.zyfpay.com%2Fupload%2Fnewsimg%2Fydzf107-10220890582.jpg&refer=http%3A%2F%2Fwww.zyfpay.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1621686156&t=3b3153d0ced148a3076cd95f506231d2"
          alt
        />
        <div>银行卡支付</div>
        <span>信用卡储蓄卡付款无需开通网银</span>
      </div>
      <div class="pay">
        <img
          class="img2"
          src="https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=1118145297,860305148&fm=26&gp=0.jpg"
          alt
        />
        <div>微信支付</div>
        <span>推荐安装微信5.0以上的用户使用</span>
      </div>
      <div class="pay">
        <img
          class="img3"
          src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fpic.baike.soso.com%2Fugc%2Fbaikepic2%2F15696%2F20170825221628-1162233375_jpg_400_320_10454.jpg%2F0&refer=http%3A%2F%2Fpic.baike.soso.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1621686321&t=b2bf13d96bfa633d53a234f8cf597b2c"
          alt
        />
        <div>支付宝支付</div>
        <span>推荐有支付宝</span>
      </div>
      <div class="sure">
        <div>确认支付</div>
      </div>
    </div>
  </div>
</template>

<script  type='text/ecmascript-6'>
export default {};
</script>

<style  lang='stylus' rel='stylesheet/stylus' scoped>
@import '../../common/stylus/mixins.styl';

.back {
  position: absolute;
  top: 0px;
  left: 0;

  .icon-zuojiantou {
    display: block;
    padding: 5px;
    font-size: 28px;
    color: black;
  }
}

.top {
  height: 35px;
  width: 100%;
  background: #fff;
  align-items: center;
  bottom-border-1px(#1e1e1e);
  display: flex;
  justify-content: center;
  font-size: 20px;
}

.mid {
  top-border-1px(#1e1e1e);
  padding-top: 15px;
  font-size: 18px;
  height: 605px;
  width: 100%;
  background: #f8f8f8;

  span {
    font-size: 5px;
  }
}

.pay {
  top-border-1px(#1e1e1e);
  height: 40px;
  display: flex;
  align-items: center;
  bottom-border-1px(#1e1e1e);
  justify-content: space-between;
}

.img1 {
  width: 38px;
}

.img2 {
  width: 31px;
}

.img3 {
  width: 43px;
}

.sure {
  height: 45px;
  font-size: 25px;
  display: flex;
  justify-content: center;
  background: #fdd503;
  align-items: center;
  border-radius: 5px;
}
</style>