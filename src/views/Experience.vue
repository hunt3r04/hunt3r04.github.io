<template>
  <div id="experience">
    <div class="overlay"></div>
    <video
      playsinline="playsinline"
      autoplay="autoplay"
      muted="muted"
      loop="loop"
    >
      <source
        src="../assets/bg-video.mp4"
        type="video/mp4"
      />
    </video>
    <div class="container h-100">
      <div class="d-flex h-100 text-center align-items-center">
        <div class="w-100 text-white">
          <div class="experience-heading mb-5">
            <h1 class="mont-300">Experience</h1>
            <h6><q class="mont-100">Do not compete if you do not have a cometetive advantage.</q></h6>
          </div>
          <div class="row">
                <div class="col hive border-right flex justify-content-between">
                     <h4 class="mont-200">June 2020 - Present</h4>
                    <div>
                        <h5 class="mb-5 mont-200">Frontend Devloper</h5>
                        <h6 class="mb-5 mont-200">Hive Link</h6>
                    </div>
                    <p class="mont-100">Designing and developing User Interfaces using frontend frameworks such as Vue.js and Angular 9.</p>
                </div>
                <div class="col ppc border-right flex justify-content-between">
                     <h4 class="mont-200">August 2018 - Aug 2019</h4>
                    <div>
                        <h5  class="mb-5 mont-200">I.T Intern</h5>
                        <h6 class="mb-5 mont-200">PPC Zimbabwe Ltd.</h6>
                    </div>
                    <p class="mont-100">Trained in the role of a Systems and LAN Administrator. Main duties entailed Server management, Network Monitoring and Optimization, Backup systems and manning the IT Helpdesk</p>
                </div>
                 <div class="col cut border-right flex justify-content-between">
                     <h4 class="mont-200">August 2016 - June 2020</h4>
                    <div>
                        <h5 class="mb-5 mont-200">Student</h5>
                        <h6 class="mb-5 mont-200">Chinhoyi University of Technology
                        <br>
                        <small><i>Bsc. Information Technology</i></small></h6>
                    </div>
                    <p class="mont-100">Majored in computer programming, Computer Networking, Machine Learning and Web Design and Development.</p>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Experience",
};
</script>
<style scoped>
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
#experience {
  position: relative;
  background-color: black;
  height: 100vh;
  min-height: 25rem;
  width: 100%;
  overflow: hidden;
}
video {
  position: absolute;
  top: 50%;
  left: 50%;
  min-width: 100%;
  min-height: 100%;
  width: auto;
  height: auto;
  z-index: 0;
  -ms-transform: translateX(-50%) translateY(-50%);
  -moz-transform: translateX(-50%) translateY(-50%);
  -webkit-transform: translateX(-50%) translateY(-50%);
  transform: translateX(-50%) translateY(-50%);
}

 .container {
  position: relative;
  z-index: 2;
}

 .overlay {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  background-color: black;
  opacity: 0.8;
  z-index: 1;
}

@media (pointer: coarse) and (hover: none) {
  #experience {
    background: url('https://source.unsplash.com/XT5OInaElMw/1600x900') black no-repeat center center scroll;
  }
   video {
    display: none;
  }
}
</style>
