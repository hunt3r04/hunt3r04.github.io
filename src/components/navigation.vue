<template>
  <div>
     <nav class="navbar navbar-expand-lg fixed-top pt-5">
        <div class="container"><a href="#" class="navbar-brand text-uppercase mont-200">Dev.zw</a>
            <button type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation" class="navbar-toggler navbar-toggler-right">
                <svg width="1.3em" height="1.3em" viewBox="0 0 16 16" class="bi bi-menu-up" fill="white" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" d="M15 3.207v9a1 1 0 0 1-1 1h-3.586A2 2 0 0 0 9 13.793l-1 1-1-1a2 2 0 0 0-1.414-.586H2a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1zm-13 11a2 2 0 0 1-2-2v-9a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2h-3.586a1 1 0 0 0-.707.293l-1.353 1.354a.5.5 0 0 1-.708 0L6.293 14.5a1 1 0 0 0-.707-.293H2z"/>
                  <path fill-rule="evenodd" d="M15 5.207H1v1h14v-1zm0 4H1v1h14v-1zm-13-5.5a.5.5 0 0 0 .5.5h6a.5.5 0 1 0 0-1h-6a.5.5 0 0 0-.5.5zm0 4a.5.5 0 0 0 .5.5h11a.5.5 0 0 0 0-1h-11a.5.5 0 0 0-.5.5zm0 4a.5.5 0 0 0 .5.5h8a.5.5 0 0 0 0-1h-8a.5.5 0 0 0-.5.5z"/>
                </svg>
            </button>
            
            <div id="navbarSupportedContent" class="collapse navbar-collapse">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item active"><a href="#home" class="nav-link text-uppercase mont-200">Home <span class="sr-only">(current)</span></a></li>
                    <li class="nav-item"><a href="#about" class="nav-link text-uppercase mont-200">About</a></li>
                    <li class="nav-item"><a href="#experience" class="nav-link text-uppercase mont-200">Experience</a></li>

                    <li class="nav-item"><a href="#" class="nav-link text-uppercase mont-200">Services</a></li>
                    <li class="nav-item"><a href="#" class="nav-link text-uppercase mont-200">Portfolio</a></li>
                    <li class="nav-item"><a href="#" class="nav-link text-uppercase mont-200">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>
  </div>
</template>
<script>

export default {
  name: "Navigation",
};
</script>

<style scoped>
.navbar {
    transition: all 0.4s;
}

.navbar .nav-link {
    color: #fff;
}

.navbar .nav-link:hover,
.navbar .nav-link:focus {
    color: #fff;
    text-decoration: none;
}

.navbar .navbar-brand {
    color: #fff;
}


/* Change navbar styling on scroll */
.navbar.active {
    background: rgb(15, 15, 15);
    box-shadow: 1px 2px 10px rgba(0, 0, 0, 0.1);
}

.navbar.active .nav-link {
    color:#fff;
}

.navbar.active .nav-link:hover,
.navbar.active .nav-link:focus {
    color:#fff;
    text-decoration: none;
}

.navbar.active .navbar-brand {
    color: rgb(180, 93, 93);
}


/* Change navbar styling on small viewports */
@media (max-width: 991.98px) {
    .navbar {
        background: rgb(19, 18, 18);
    }

    .navbar .navbar-brand, .navbar .nav-link {
        color: rgb(255, 255, 255);
    }
}

</style>
