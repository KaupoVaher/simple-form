<template>
<link href="/style/accesories.css" rel="stylesheet" type="text/css">
<div>
  <button class="round-btn">+</button>
</div>

  <div>
    <EnquiryBox />
  </div>




</template>

<script>

 import EnquiryBox from "@/components/EnquiryBox";

export default {
  name: 'App',
  components: {
      EnquiryBox
  }

}
</script>

<style>

</style>
