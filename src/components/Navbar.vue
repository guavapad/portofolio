<template>
<!-- navbar start -->
  <div class="row ">
    <div class="col"> 
      <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top shadow-sm">
        <div class="container-fluid">
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0 ">
              <li class="nav-item">
                <a class="nav-link text-warning fw-bold" aria-current="page" href="#home">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link text-warning fw-bold" href="#about">About</a>
              </li>
              <li class="nav-item">
                <a class="nav-link text-warning fw-bold" href="#porto">Portofolio</a>
              </li>
              <li class="nav-item">
                <a class="nav-link text-warning fw-bold" href="#contact">Contact</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </div>
  <!-- navbar end -->
  <div>
    <div class="container-lg" >
      <!-- home start -->
            <div class="row min-vh-100 py-5 align-items-center align-content-center" id="home">
              <div class="col-md-6 mt-5 mt-md-0">
                <p class="text-muted mb-1">Hello I'm</p>
                <h1 class="text-warning text-uppercase fs-1 fw-bold">A Web Developer</h1>
                <h1 class="text-warning fs-4">Fasluki Perdana</h1>
                <p class="text-muted mb-1">Saya adalah seorang Web Developer khususnya di bidang Frontend, semoga anda tertarik melihat web portofolio saya</p>
                <a href="#porto" class="btn btn-warning px-3 mt-3 text-white">My work</a>
              </div>
              <div class="col-md-6 text-center mt-5 mt-md-0">
                <img src="../assets/foto.jpg" id="img-about" class="shadow-lg w-50" alt="...">
              </div> 

            </div>
            
            <!-- home end -->
            
            <!-- about start -->
            <section class="about bg-white py-5" id="about">
              <div class="container-lg py-4">
                <div class="row justify-content-center" >
                  <div class="col-lg-8">
                    <div class="section-title text-center">
                        <h2 class="text-uppercase fw-bold text-warning">About Me</h2>
                    </div>
                  </div>
                <div class="row py-5">
                  <div class="col-md-6 mt-5 mt-md-0 about-text">
                    <!-- <h4>Vel nihil similique saepe reprehenderit quam nobis sit illum adipisci numquam?</h4> -->
                    <p class="text-muted mb-3">Haii, nama saya fasluki perdana saya biasa dipanggil luki berusia 23 tahun, saya merupakan fresh graduate dari Politeknik Negeri Padang. Saya sangat tertarik pada bidang IT terutama dalam bidang web design, saya adalah orang yang berkeinginan kuat untuk belajar, bisa bekerja sama dengan tim, jujur, dan bertanggung jawab serta memilki kemampuan komunikasi verbal dan lisan yang baik.                </p>
                    <div class="skill-item mb-4">
                      <h3 class="fs-6">HTML</h3>
                      <div class="progress" style="height: 5px;">
                        <div class="progress-bar bg-warning" role="progressbar" style="width: 75%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
                        </div>
                      </div>
                    </div>
                    <div class="skill-item mb-4">
                      <h3 class="fs-6">CSS</h3>
                      <div class="progress" style="height: 5px;">
                        <div class="progress-bar bg-warning" role="progressbar" style="width: 75%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
                        </div>
                      </div>
                    </div>
                    <div class="skill-item mb-4">
                      <h3 class="fs-6">Javascript</h3>
                      <div class="progress" style="height: 5px;">
                        <div class="progress-bar bg-warning" role="progressbar" style="width: 70%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
                        </div>
                      </div>
                    </div>
                    <div class="skill-item mb-4">
                      <h3 class="fs-6">React Js</h3>
                      <div class="progress" style="height: 5px;">
                        <div class="progress-bar bg-warning" role="progressbar" style="width: 60%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
                        </div>
                      </div>
                    </div>
                    <div class="skill-item mb-4">
                      <h3 class="fs-6">Mysql</h3>
                      <div class="progress" style="height: 5px;">
                        <div class="progress-bar bg-warning" role="progressbar" style="width: 70%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
                        </div>
                      </div>
                    </div>
                  </div>
                  
                  <div class="col-md-6 mt-5 mt-md-0 text-center">
                    <img src="../assets/about.jpeg" id="img-about" class="shadow-lg w-50" alt="...">
                  </div>
                </div>
                </div>
              </div>
            </section>
            
            <!-- about end -->
            <!-- service start -->
            <section class="service py-5">
              <div class="container-lg py-4">
                <div class="row justify-content-center">
                  <div class="col-lg-8">
                    <div class="section-title text-center">
                        <h2 class="fw-bold text-uppercase mb-5 text-warning">What I do</h2>
                    </div>
                  </div>
                </div>
                <div class="row text-center">
                  <div class="col-md-6 col-lg-4 mb-4">
                    <div class="service-item shadow-sm p-4 rounded bg-white">
                      <div class="icon my-3 text-warning fs-2">
                        <i class="fas fa-code"></i>
                      </div>
                      <h3 class="fs-5 py-2">Web Development</h3>
                      <p class="text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. A maxime illo fugiat ipsam praesentium impedit optio debitis doloremque, sunt, accusamus itaque officia pariatur aut mollitia suscipit. Vitae tenetur molestias aspernatur?</p>
                    </div>
                  </div>
                  <div class="col-md-6 col-lg-4 mb-4">
                    <div class="service-item shadow-sm p-4 rounded bg-white">
                      <div class="icon my-3 text-warning fs-2">
                        <i class="fas fa-lightbulb"></i>
                      </div>
                      <h3 class="fs-5 py-2">Creative Idea</h3>
                      <p class="text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. A maxime illo fugiat ipsam praesentium impedit optio debitis doloremque, sunt, accusamus itaque officia pariatur aut mollitia suscipit. Vitae tenetur molestias aspernatur?</p>
                    </div>
                  </div>
                  <div class="col-md-6 col-lg-4 mb-4">
                    <div class="service-item shadow-sm p-4 rounded bg-white">
                      <div class="icon my-3 text-warning fs-2">
                        <i class="fas fa-image"></i>
                      </div>
                      <h3 class="fs-5 py-2">Web Design</h3>
                      <p class="text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. A maxime illo fugiat ipsam praesentium impedit optio debitis doloremque, sunt, accusamus itaque officia pariatur aut mollitia suscipit. Vitae tenetur molestias aspernatur?</p>
                    </div>
                  </div>
                </div>
              </div>
            </section>
            <!-- service end -->
            <!-- porto start -->
            <section class="portofolio py-5" id="porto">
              <div class="container-lg py-4">
                <div class="row justify-content-center">
                  <div class="col-lg-8">
                    <div class="section-title text-center">
                      <h2 class="fw-bold mb-5 text-uppercase text-warning">My Portofolio</h2>
                    </div>
                  </div>
                </div>
                <div class="row" >
                  <div class="col-md-6 col-lg-4" >
                    <div class="portofolio-item">
                      <img src="../assets/kasir-app.png" class="w-100" alt="">
                      <h3 class="text-capitalize fs-5 my-2">Kasir App</h3>
                      <p class="mb-4"><a href="#" class="text-danger text-decoration-none">Using React Js</a></p>
                    </div>  
                  </div>
                  <div class="col-md-6 col-lg-4" >
                      <div class="portofolio-item">
                        <img src="../assets/emenu.jpg" class="w-100" alt="">
                        <h3 class="text-capitalize fs-5 my-2">E-menu</h3>
                        <p class="mb-4"><a href="#" class="text-danger text-decoration-none">Using Codeigniter 3</a></p>
                      </div>  
                  </div>
                  <div class="col-md-6 col-lg-4" >
                        <div class="portofolio-item">
                          <img src="../assets/company-profile.png" class="w-100" alt="">
                          <h3 class="text-capitalize fs-5 my-2">Company Profile</h3>
                          <p class="mb-4"><a href="#" class="text-danger text-decoration-none">Using Css And Javascript</a></p>
                        </div>  
                    </div>
                </div>
              </div>
            </section>
            
            <!-- porto end -->
            <!-- contact start -->
            <section class="py-5 bg-warning" id="contact">
              <div class="container-lg py-4">
                <div class="row justify-content-center" >
                  <div class="col-lg-8 text-center">
                    <p class="text-light fs-5">
                      Do you have any project?
                    </p> 
                    <h2 class="fs-1 text-white mb-4">I'm available for freelance project</h2>
                  </div>
                </div>
              </div>
            </section>
            <section class="py-5">
              <div class="container-lg py-4">
                <div class="row justify-content-center">
                  <div class="col-lg-8">
                    <div class="section-title text-center">
                      <h2 class="fw-bold mb-5 text-warning">Contact Me</h2>
                    </div>
                  </div>
                </div>
                <div class="row align-content-center">
                  <div class="col-md-4">
                    <div class="contact-item d-flex mb-3">
                      <div class="icon fs-4 text-warning">
                          <i class="fas fa-envelope"></i>
                      </div>
                      <div class="text ms-3">
                          <h3 class="fs-5">Email</h3>
                          <p class="text-muted">perdanafasluki@gmail.com</p>
                      </div>
                    </div>
                  </div>
                  <div class="col-md-4">
                    <div class="contact-item d-flex mb-3">
                      <div class="icon fs-4 text-warning">
                          <i class="fas fa-phone"></i>
                      </div>
                      <div class="text ms-3">
                          <h3 class="fs-5">Phone</h3>
                          <p class="text-muted">0823 8644 7268</p>
                      </div>
                    </div>
                  </div>
                  <div class="col-md-4">
                    <div class="contact-item d-flex mb-3">
                      <div class="icon fs-4 text-warning">
                          <i class="fa-brands fa-instagram"></i>
                      </div>
                      <div class="text ms-3">
                          <h3 class="fs-5">instagram</h3>
                          <p class="text-muted">@faslukiperdanaa</p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
               
            </section>
            
            <!-- contact end -->
      </div>
  </div>
</template>