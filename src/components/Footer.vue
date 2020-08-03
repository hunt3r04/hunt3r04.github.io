<template>
  <div id="footer">
    <div class="d-flex footer-dev justify-content-around align-items-center">
      <div class="copyright">
        <p>All Rights Reserved @ Devzw 2020</p>
      </div>
      <div class="socials d-flex justify-content-center">
        <div class="linkedin mr-4">
          <a
            class="text-white"
            href="https://www.linkedin.com/in/muvimi-bongani/"
            ><i class="fab fa-linkedin"></i
          ></a>
        </div>
        <div class="github mr-4 ">
          <a class="text-white" href="https://github.com/hunt3r04"
            ><i class="fab fa-github"></i
          ></a>
        </div>
        <div class="twitter mr-4">
          <a href=""><i class="fab fa-twitter-square"></i></a>
        </div>
      </div>
      <div class="design">
        <p class="text-white p-2">Developed By : <a href="devzw.tech">Devzw</a></p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Footer",
};
</script>

<style lang="css" scoped>
#footer {
  background: rgb(15, 15, 15);
}
.footer-dev{
    min-height: 100px;
}
</style>
