<template>
  <div class="row">
    <div class="col-12">

      <div class="text-start px-4 d-grid gap-3 ">
        <h3>Submit a Ticket</h3>
        <div class="d-grid gap-0">
          <label class="col-form-label col-form-label-lg">First name</label>
          <input type="text" class="form-control form-control-lg">
        </div>
        <div class="d-grid gap-0">
          <label class="col-form-label col-form-label-lg">Activehosted URL</label>
          <input type="text" class="form-control form-control-lg">
        </div>
        <div class="d-grid gap-0">
          <label class="col-form-label col-form-label-lg">Message</label>
          <textarea type="text" class="form-control form-control-lg"></textarea>
        </div>
        <div class="text-start px-4 d-grid gap-0 container">

          <button class="btn btn-primary btn-lg"> Send Enquiry</button>
        </div>

    </div>
      </div>
    </div>


</template>

<script>
export default {
  name: "EnquiryBox"
}
</script>

<style scoped>

</style>