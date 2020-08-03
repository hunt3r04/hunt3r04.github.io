<template>
  <div id="contact-me">
  <div class="h100"></div>
    <div class="container">
        <div class="row">
      
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