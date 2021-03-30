<template>
  <div id="footer" class="container-fluid">
    <div class="logo">
      <img src="@/assets/img/logo_white.png" alt="logo">
    </div>
    <p class="title">北京金睛云华有限公司沈阳分公司</p>
    <p class="address_tel_fax">
      <span>地址：沈阳市浑南区上深沟村860-1号 沈阳国际软件园E03-10层</span>
      <span>  Tel：024-23880730</span>
      <span>  Fax：8888-88888888</span>
    </p>
    <p class="email_wx">
      <span>邮箱：vampire1961@outlook.com</span>
      <span>  公司微信号：在下魔王123</span>
    </p>
    <p class="copy">Copyright &copy; 2021 北京金睛云华有限公司</p>
  </div>
</template>
<script>
export default {
  name: "Footer",
  data() {
    return {};
  }
};
</script>
<style scoped>
#footer {
  width: 100%;
  height: 100%;
  color: #fff;
  background: #036;
  overflow: hidden;
  text-align: center;
}
.logo {
  width: 95px;
  height: 45px;
  margin: 50px auto 20px;
}
.title {
  font-size: 25px;
  margin-bottom: 20px;
}
.address_tel_fax {
  color: #d3d3d3;
  font-size: 14px;
  margin: 10px 0;
}
.email_wx {
  color: #d3d3d3;
  font-size: 14px;
}
.copy {
  color: #d3d3d3;
  font-size: 14px;
  margin: 50px 0 10px;
}
@media screen and (max-width: 997px) {
  .title {
    font-size: 20px;
  }
  .address_tel_fax {
    font-size: 12px;
  }
  .email_wx {

  font-size: 12px;
}
.copy {
  font-size: 12px;
  margin: 30px 0 10px;
}
}
</style>

