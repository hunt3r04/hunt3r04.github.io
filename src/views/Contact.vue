<template>
  <div id="contact-me" class="container">
    <div class="row">
      <div class="col-md-4">
        <div class="contact-details">
          <div class="email">
            <h6 class="mont-200">bongani.muvimi@devzw.tech</h6>
          </div>
          <div class="pnone">
            <h6 class="mont-200">+263 71 8566 208</h6>
          </div>
          <div class="address">
            <h6 class="mont-200">Chinhoyi, Zimbabwe, Africa, Earth</h6>
          </div>
          <div class="socials d-flex">
            <div class="linkedin">
              <a href="https://www.linkedin.com/in/muvimi-bongani/"></a>
            </div>
            <div class="github">
              <a href=""></a>
            </div>
            <div class="twitter">
              <i></i>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-8">
        
        <div class="form-group p-5">
        <div><h2 class="mont-300">I am always looking for great collaborators. Let’s message me and make something together!</h2></div>
          <form action="" method="post">
            <div class="d-flex">
              <div class="input-group">
                <label for="Name">Your Name (required)</label>
                <input
                  type="text"
                  class="form-control"
                  name="full_name"
                  placeholder="Your Name"
                />
              </div>
              <div class="input-group">
                <label for="Email">Your Email (required)</label>
                <input
                  type="email"
                  class="form-control"
                  name="email"
                  placeholder="Your Email"
                />
              </div>
            </div>
            <div class="d-flex">
            
                <div class="input-group">
                <label for="Category">Category (optional)</label>
                <input
                  type="text"
                  class="form-control"
                  name="category"
                  placeholder="Category"
                />
              </div>
              <div class="input-group">
                <label for="Mobile">Mobile (required)</label>
                <input
                  type="text"
                  class="form-control"
                  name="full_name"
                  placeholder="Your Name"
                />
              </div>
            </div>//
            <div class="input-group">
                <label for="Message">Your Message</label>
                <textarea name="message" class="form-control"></textarea>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
    name:'Contact'
}
</script>