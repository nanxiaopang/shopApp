<template>
  <section class="order">
    <HeaderTop title="订单列表"></HeaderTop>
    <section class="order_no_login">
      <img src="./order/person.png">
      <h3>登录后查看外卖订单</h3>
      <button>立即登陆</button>
    </section>
  </section>
</template>

<script>
  import HeaderTop from '../../components/HeaderTop/HeaderTop.vue'
  export default {
    components: {
      HeaderTop
    }
  }
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">

#app >section.order {
  width: 100%;
}
#app >section.order .order_no_login {
  padding-top: 140px;
  width: 60%;
  margin: 0 auto;
  text-align: center;
}
#app >section.order .order_no_login >img {
  display: block;
  width: 100%;
  height: 30%;
}
#app >section.order .order_no_login >h3 {
  padding: 10px 0;
  font-size: 17px;
  color: #6a6a6a;
}
#app >section.order .order_no_login >button {
  display: inline-block;
  background: #02a774;
  font-size: 14px;
  color: #fff;
  border: 0;
  outline: none;
  border-radius: 5px;
  padding: 10px 20px;
}
</style>
