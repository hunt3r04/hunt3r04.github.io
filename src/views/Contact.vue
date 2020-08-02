<template>
  <div id="contact-me">
  <div class="h100"></div>
    <div class="container">
        <div class="row">
      <div class="col-md-4 p-5 align-items-center">
        <h1 class="mont-300 text-white">Contact</h1>
        <div class="contact-details">
          <div class="email">
            <h6 class="mont-200 text-white">bongani.muvimi@devzw.tech</h6>
          </div>
          <div class="pnone">
            <h6 class="mont-200 text-white">+263 71 8566 208</h6>
          </div>
          <div class="address">
            <h6 class="mont-200 text-white">Chinhoyi, Zimbabwe, Africa, Earth</h6>
          </div>
          <div class="socials d-flex justify-content-center">
            <div class="linkedin mr-2">
              <a href="https://www.linkedin.com/in/muvimi-bongani/"><i class="fab fa-linkedin"></i></a>
            </div>
            <div class="github mr-2">
                
                <a href="https://github.com/hunt3r04"><i class="fab fa-github"></i></a>
            </div>
            <div class="twitter mr-2">
              <a href=""><i class="fab fa-twitter-square"></i></a>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-8">
        
        <div class="form-group p-5">
        <div>
            <h2 class="mont-200 text-white">Lets's Collaborate On A Project And <span class="text-red">Make Dreams Into Reality</span>!</h2>
        </div>
          <form action="" method="post">
            <div class="d-flex">
              <div class="input-group">
                <label class="w100" for="Name">Your Name (required)</label>
                <input
                  type="text"
                  class="form-control"
                  name="full_name"
                  placeholder="Your Name"
                />
              </div>
              <div class="input-group ml-2">
                <label class="w100"  for="Email">Your Email (required)</label>
                <input
                  type="email"
                  class="form-control"
                  name="email"
                  placeholder="Your Email"
                />
              </div>
            </div>
            <div class="d-flex ">
                <div class="input-group">
                <label class="w100"  for="Category">Category (optional)</label>
                <input
                  type="text"
                  class="form-control"
                  name="category"
                  placeholder="Category"
                />
              </div>
              <div class="input-group ml-2">
                <label class="w100" for="Mobile">Mobile (required)</label>
                <input
                  type="text"
                  class="form-control"
                  name="full_name"
                  placeholder="Your Name"
                />
              </div>
            </div>
            <div class="input-group">
                <label class="w100" for="Message">Your Message</label>
                <textarea name="message" class="form-control" placeholder="Your Message"></textarea>
            </div>
            <button class="btn btn-danger btn-lg mt-3">Contact Me</button>
          </form>
        </div>
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
<style scoped>
    #contact-me{
        background: url('../assets/img/contact-bg.png');
        min-height: 100vh;
        width:100vw;
    }
    input[type=text],textarea[name=message], input[type=email]{
        background: rgba(0,0,0,0.4);
        padding:5px;
        border: 1px solid rgba(0,0,0,0.8);
    }
    .w100{
        width:100%;
    }
    .h100{
        height:100px;
    }
    .mont-200{
    font-family: 'Montserrat', sans-serif;
    font-weight: 200;
}
.mont-100{
    font-family: 'Montserrat', sans-serif;
    font-weight: 100;
}
.mont-300{
    font-family: 'Montserrat', sans-serif;
    font-weight: 300;
}
label{
    margin-top: 10px;
    color:rgba(255,255,255,0.5);
}
.f-15{
    font-size: 15px;
}
.text-red{
    color:darkred;
}
</style>