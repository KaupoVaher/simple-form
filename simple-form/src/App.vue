<template>
<link href="/style/App.css" rel="stylesheet" type="text/css">
  <div class="round-button">
    <RoundButton />
  </div>

  <div>
    <EnquiryBox />
  </div>
  <div class="box"></div>
  <div class="instant-answer">
    <InstantAnswer />
  </div>



</template>

<script>

 // import EnquiryBox from "@/components/EnquiryBox";
 import RoundButton from "@/components/RoundButton.vue";
import InstantAnswer from "@/components/InstantAnswer.vue";
export default {
  name: 'App',
  components: {
      // EnquiryBox,
    RoundButton, InstantAnswer
  }

}
</script>
