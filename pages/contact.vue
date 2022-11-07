<template>
<div class="dmartContactPage">
<div class='container'>
<div class="row">
          <div class='col-md-12 p-3'>
          <h2 class='text-center'>Contact us</h2>
          </div>
        </div>
<section class='forStyle'>
  <div class="container px-3 py-4">
    <div class="row">
      <div class="col-md-12">
            <form>
              <div class="mb-3">
                <label for="name" class="form-label">Name</label>
                <input name='name' type="text" class="form-control" id="name" aria-describedby="emailHelp">
                <div id="emailHelp" class="form-text" list="off">We'll never share your email with anyone else.</div>
              </div>
              <div class="mb-3">
                <label for="Email1" class="form-label">Email address</label>
                <input name='email' type="email" class="form-control" id="Email1" aria-describedby="emailHelp">
                <div id="emailHelp" class="form-text" list="off">We'll never share your email with anyone else.</div>
              </div>
              <div class="mb-3">
                <label for="Address" class="form-label">Address</label>
                <input type="text" class="form-control" id="Address">
              </div>
              <div class="mb-3">
                <label for="Message" class="form-label">Message</label>
                <textarea name='sms' class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
              </div>
              <div class="mb-3 form-check">
                <input type="checkbox" class="form-check-input" id="exampleCheck1">
                <label class="form-check-label" for="exampleCheck1">Agree with all term & condition</label>
              </div>
                <button type="submit" class="btn btn-primary">Submit</button>
            </form>
      </div>
    </div>
  </div>
</section>

<section>
    <div class='container p-3 '>       
        <div class="row">
          <div class="col-md-12 rounded-3 bg-gray">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3649.7049235869845!2d90.41789591478566!3d23.82908968455061!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3755c72c6238452f%3A0x5b1b58ce3e37a804!2sKhilkhet%20Bus%20stop!5e0!3m2!1sen!2sbd!4v1667594069388!5m2!1sen!2sbd" 
            width="100%" 
            height="450" 
            class='p-1 m-1 rounded-3'
            style="border:0;" 
            allowfullscreen="" 
            loading="lazy" 
            referrerpolicy="no-referrer-when-downgrade">
            </iframe>
          </div>
        </div>
    </div>
</section>
</div>
</div>
</template>
<script>
export default {
    name:'contact',
     head: {
    title: 'Contact',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'dMart Contact page'
      },
      {
        hid: 'keywords',
        name: 'keywords',
        content: 'vue,vuejs,dmart,javaScript,digital marketing, javascript- contactpage'
      }
    ],
  }
}


</script>