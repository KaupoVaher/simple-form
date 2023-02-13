<template>
  <div class="col-xl-10 col-xxl-10 text-title">
    <h2>For Enquiries</h2>
    <p>Kindly send your enquiry. Your Account Manager will respond shortly</p>
  </div>

  <div class="col-md-10 col-sm-12 text-title">
    <div class="card">
      <div class="card-body">
        <h3 class="help-card-title">Contact us</h3>
        <form method="post" action="/help/send">
          <div class="row">
            <div class="col">
              <label for="first-name" class="form-label">First name</label>
              <input id="first-name" class="form-control" disabled="disabled">
            </div>
            <div class="col">
              <label for="activehosted-url" class="form-label">Activehosted URL</label>
              <input id="activehosted-url" class="form-control"  disabled="disabled">
            </div>
          </div>
          <div class="row">
            <div class="col">
              <label for="email" class="form-label">Email address</label>
              <input id="email" class="form-control"  disabled="disabled">
            </div>
          </div>
          <div class="row">
            <div class="col">
              <label for="message" class="form-label">Message</label>
              <textarea class="form-control" id="message" name="message"></textarea>
            </div>
          </div>
          <div class="row">
            <div class="col button-section d-flex">
              <button type="submit" class="btn btn-primary">Send enquiry</button>
            </div>
            <div class="small text-danger" id="error-msg" style="display: none"></div>
          </div>

        </form>
        <div class="m-3"></div>

        <div class="alert alert-primary" role="alert" hide-after="3000">
          We couldn't send the message
        </div>


        <div class="alert alert-success" role="alert" hide-after="3000">
          Message sent!
        </div>

      </div>
    </div>
  </div>

  <div class="modal" id="message-confirmation-modal" tabindex="-1">
    <div class="modal-dialog modal-dialog-centered">
      <div class="modal-content bg-tertiary">
        <div class="modal-header border-0 text-center">
          <p>Thanks for your submission!</p>
          <button type="button" style="min-width: 16px;" class="btn-close btn-close-white bg-light"
                  data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'


export default {
  name: 'HomeView',
  components: {
    // HelloWorld
  }
}
</script>
