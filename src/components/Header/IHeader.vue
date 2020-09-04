<template>
  <header>
    <div class="row">
      <div class="col-12 col-md-6">
        <h1>
          <a href="#">
            <img alt="Vue logo" src="../../assets/logo.png" />
          </a>
        </h1>
      </div>
      <div class="col-md-6 col-12 text-right pt-3 header-item">
        <a class="search-icon mr-3">
          <i class="icon-search"></i>
        </a>
        <a href="#" class="mr-3 create-account">إنشاء حساب</a>
        <button class="btn login">تسجيل الدخول</button>
      </div>
    </div>
    <hr />
  </header>
</template>

<style lang="scss" scoped>
@import "./HeaderComponent.scss";
</style>
<script>
export default {
  name: "IHeader",
};
</script>