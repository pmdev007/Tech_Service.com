<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=, initial-scale=1.0">
      
        <style rel = "stylesheet" href = "bootstarap\bootstrapproject\style.css" ></style>

        <!-- bootstarap css cdn -->
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    
         <!-- bootstrap icons cdn -->

         <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.0/font/bootstrap-icons.css">
      
     
    <title>boot one</title>
</head>
<body>
    
    <!-- nav bar section start ------------------------------------------------------------------------------------>
   

    <nav class="navbar navbar-expand-lg navbar-light  "  style="background-color: #7c93a3;">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">pratik logo</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">About us </a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Services
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li><a class="dropdown-item" href="#">web developnment</a></li>
                <li><a class="dropdown-item" href="#">Android developnment</a></li>
                <li><hr class="dropdown-divider"></li>
                <li><a class="dropdown-item" href="#">Data sceince</a></li>
                <li><a class="dropdown-item" href="#">Blockchain</a></li>
                <li><a class="dropdown-item" href="#"> ML-DL </a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"> contact us </a>
            </li>
          </ul>
          <form class="d-flex">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
    
    <!-- nav bar ends  -->


     <!-- slider starts from here  -->

     <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="https://www.seotactica.com/wp-content/uploads/2020/03/expert-developers.gif" height="450px"  class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5  > we developnment </h5>
            <p> we are the giants in web developnment</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src= " data:image/jpeg;base64,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 " height="450px"    class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>Second slide label</h5>
            <p>Some representative placeholder content for the second slide.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="data:image/png;base64,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" height="450px"   class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>Third slide label</h5>
            <p>Some representative placeholder content for the third slide.</p>
          </div>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>

     <!-- slider end here  -->
      <div class = "container-fluid">
        <div class = "row">
          <div class = "col-12">
            <h3  class="display-6 text-center mt-5 mb-5"> Lorem ipsum dolor sit amet consectetur, adipisicing  elit <br>. Ab, sed. and he is the developer  </h3>
          </div>
        </div>

         <!-- features of our website -->

         <div class = "row justify-content-evenly mt-5 ">
          <div class = "col-md-3 text-center mb-5">
         <h1> <i class="bi bi-file-code-fill text-primary"></i></h1>
         <h5> build for developers</h5>
         <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Recusandae, tempora and he have another.</p>
        </div>
         <div class = "col-md-3 text-center mb-5">
          <h1><i class="bi bi-easel-fill text-danger"></i></h1>
          <h5> build for developers</h5>
          <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Recusandae, tempora and he have another.</p>
         </div>
         <div class = "col-md-3 text-center mb-5">
         <h1> <i class="bi bi-calendar-range-fill text-success"></i> </h1>
         <h5> build for developers</h5>
         <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Recusandae, tempora and he have another.</p>
         </div>
    
          <!-- feature end here and line starts from here  -->

        <hr>
     
        <!-- line end and growth section starts from here  -->

        <div class = "row justify-content-evenly pt-3 pb-5">
          <div class = "col-md-5">
             <img src = "https://i.pinimg.com/originals/50/78/a0/5078a05eb1b6847d93383eaa4c0ed500.gif" height="300px" style="width:320px;" class = "image-fluid" >
        </div>
         
        <div class = "col-md-5 ">
          <h5 class = "mt-3"> website developnment</h5>
          <div class="progress">
            <div class="progress-bar bg-success" role="progressbar" style="width: 25%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
          </div>
          <h5 class = "mt-3"> App developnment</h5>
          <div class="progress">
            <div class="progress-bar bg-info" role="progressbar" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
          </div>
            <h5 class = "mt-3"> Data Science </h5>
          <div class="progress">
            <div class="progress-bar bg-warning" role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
          </div>
          <h5 class = "mt-3"> Blockchain</h5>
          <div class="progress">
            <div class="progress-bar bg-danger" role="progressbar" style="width: 100%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
          </div>
          <h5 class = "mt-3">ML-DL</h5>
          <div class="progress">
            <div class="progress-bar bg-primary" role="progressbar" style="width: 100%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
          </div>
        </div>

        <hr class = "mt-5">
         <!-- line end here  -->

         <!-- contact form starting from here  -->

         <div class = "row pt-2 p-5 justify-content-md-evenly" style="background-color: #f1f1f1;">
           <div class =  "col-md-5 mt-5">
             <h3>contact form</h3>
            <form>
              <div class="mb-3">
                <label for="exampleInputEmail1" class="form-label">enter name </label>
                <input type="text" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
              </div>

              <div class="mb-3">
                <label for="exampleInputEmail1" class="form-label">Email address</label>
                <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
              </div>

              <div class="mb-3">
                <label for="exampleFormControlTextarea1" class="form-label">write comment or any doubt</label>
                <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
              </div>
        
              <div class="mb-3 form-check">
                <input type="checkbox" class="form-check-input" id="exampleCheck1">
                <label class="form-check-label" for="exampleCheck1">Check me out</label>
              </div>
              <button type="submit" class="btn btn-primary">Submit</button>


            </form>

        </div>

          <div class = "col-md-5 mt-5">
            <h3 class = "mb-4" >Address</h3>
             <p> 104 , mauli co-op , mahada colony <br>
              mankhurd-mumbai 400043 <br>
              <i class="bi bi-telephone-fill"></i> : 9321499349
            </p>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d30171.668403907646!2d72.90467152903689!3d19.043566241908106!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3be7c6701642b56d%3A0x78bac254fd112b42!2sMauli%20Co-operative%20Housing%20Society!5e0!3m2!1sen!2sin!4v1636922838344!5m2!1sen!2sin" style = "width:100%;" height="310" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
          </div>
        </div>


     <!-- faq secion has started from here  -->
       
     <div class = "row justify-content-evenly pt-5 pb-5">
       <div class = "col-md-10">
         <h3 class = "text-center mb-4"> FAQ </h3>
         <div class="accordion accordion-flush border" id="accordionFlushExample">
          <div class="accordion-item">
            <h2 class="accordion-header" id="flush-headingOne">
              <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
                Accordion Item #1
              </button>
            </h2>
            <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
              <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the first item's accordion body.</div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="flush-headingTwo">
              <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
                Accordion Item #2
              </button>
            </h2>
            <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
              <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the second item's accordion body. Let's imagine this being filled with some actual content.</div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="flush-headingThree">
              <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
                Accordion Item #3
              </button>
            </h2>
            <div id="flush-collapseThree" class="accordion-collapse collapse" aria-labelledby="flush-headingThree" data-bs-parent="#accordionFlushExample">
              <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the third item's accordion body. Nothing more exciting happening here in terms of content, but just filling up the space to make it look, at least at first glance, a bit more representative of how this would look in a real-world application.</div>
            </div>
          </div>
        </div>
       </div>

     </div>

        
         </div>

        </div>
         <!-- footer section start form here  -->
         <div container = "container-fluid ">
        <div class = "  row justify-content-evenly bg-dark text-white pt-2 pb-5">
          
          <div class = "col-md-3 pt-5 text-start" >
            <h5 class = "pb-2"> PM Art</h5>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Praesentium ut, eaque perspiciatis nobis quos et? Nobis?</p>
          </div>
          <div class = "col-md-3 pt-5">
            <h5 class = "pb-2">Important Links</h5>
            <p>
              <a href="#" class = "link-light text-decoration-none" >Home</a>
              <br>
              <a href="#" class = "link-light text-decoration-none" >About us</a>
              <br>
              <a href="#" class = "link-light text-decoration-none" >Contact us</a>
               <br>
               <a href="#" class = "link-light text-decoration-none" > Our clients</a>
               <br>
               <a href="#" class = "link-light text-decoration-none" >Our team</a>
            </p>
          </div>
          <div class = "col-md-3 pt-5" > 
             <h5 class="pb-2"> Contact us</h5>
            <p>
              104 , mauli co-op , mahada colony <br>
              mankhurd-mumbai 400043 <br>
              <i class="bi bi-telephone-fill"></i> : 9321499349
            </p>
           </div>
        </div>
        </div>

         <!-- copyright section starts from here  -->
         <div>
           <div class = "row bg-secondary text-white text-center"> 
             <div class = "col-12">
               <p class = "p-3"> copyright &copy; 2018-2021 by PM art  All Rights Reserved. </p>
             </div>
           </div>

         </div>
      
     <!-- the cdn for the java script of the bootstrap  -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
    

</body>
</html>
