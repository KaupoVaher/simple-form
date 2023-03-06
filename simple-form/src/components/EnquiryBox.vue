<template>

  <link href="/style/EnquiryBox.css" rel="stylesheet" type="text/css">

      <div class="frame bottom-right">
        <div class="title">
        Submit a Ticket
        </div>
        <div class="margin-top">
          <div class="label">
            <label>First name</label>
          </div>
          <div>
            <font-awesome-icon class="icon-fn" icon="fa-solid fa-eye-slash" />
            <input type="text" class="input">

          </div>

        </div>
        <div class="margin-top">
          <div class="label">
            <label>Activehosted URL</label>
          </div>
          <div>
            <font-awesome-icon class="icon-au" icon="fa-solid fa-eye-slash" />
            <input type="text" class="input">
          </div>
        </div>
        <div class="margin-top">
        <div class="label">
          <label>Message</label>
          </div>
        <div>
          <textarea class="text-area"></textarea>
        </div>
        </div>

        <div class="margin-top">
          <button class="button">
            <div id="text">
              Send Enquiry
            </div>
          </button>
        </div>
      </div>




</template>

<script>
export default {
  name: "EnquiryBox"
}
</script>
