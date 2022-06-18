<template>
  <div class="view container-fluid">
    <HomePage></HomePage>
    <div class="row">
      <div class="col-lg-7">
        <TeacherInfo></TeacherInfo>
        <HelloWorld></HelloWorld>
      </div>
      <div class="col-lg-5">
        <PricingTemplate></PricingTemplate>
      </div>
    </div>
    <RequirementsTemplate></RequirementsTemplate>
    <ContactTemplate></ContactTemplate>
  </div>
  <FootersTemplate></FootersTemplate>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import HomePage from '@/components/Home.vue'
import TeacherInfo from '@/components/Teacher'
import FootersTemplate from '@/components/Footers'
import ContactTemplate from '@/components/Contact'
import RequirementsTemplate from '@/components/Requirements'
import PricingTemplate from '@/components/Pricing'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    HomePage,
    TeacherInfo,
    FootersTemplate,
    ContactTemplate,
    RequirementsTemplate,
    PricingTemplate
  }
}
</script>
<style scoped lang="stylus">
.view {
  width: 90% !important;
}
</style>