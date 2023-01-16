<template>
  <div class="about">
    <div class="container-fluid h-100">
      <div class="row h-100">
        <div class="col-md-9 h-100 d-flex justify-content-center align-items-center">
         <div class="col-md-5 rounded px-5 py-4 shadow bg-white text-right">

          <EnquiryBox />

        </div>
      </div>
    </div>
    </div>
  </div>
</template>
<script>
import EnquiryBox from '@/components/EnquiryBox.vue'


export default {
  name: 'AboutView',
  components: {
    EnquiryBox
  }
}
</script>
