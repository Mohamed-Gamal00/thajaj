<script setup>
import NavBarCom from '../components/layout/NavBarCom.vue';
import FooterCom from '../components/layout/FooterCom.vue';
import ServicesCom from '@/components/services/ServicesCom.vue'
</script>

<template>
  <NavBarCom />
  <div>
    <!-- خدماتنا 2 -->
    <div class="container-fluid">
      <div class="row d-flex justify-content-center text-center my-lg-3 py-lg-3 banner-header">
        <strong>
          <h2 class="fw-900" style="font-size: 30px">خدمتنا</h2>
          <p class="text-center">تعرف علي ما نقدمة بمزيد من التفاصيل التوضيحية</p>
        </strong>
      </div>
      <ServicesCom />
  </div>
  </div>
  <FooterCom />
</template>

<style lang="scss" scoped></style>
