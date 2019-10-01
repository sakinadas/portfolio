<!DOCTYPE html>
<html lang="en">
<head>
  <title>Sakina Das</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  
  <!-- <link rel="stylesheet" href="bootstrap.css" crossorigin="anonymous"> -->
  <link rel="stylesheet" href="css/custom-bootstrap.css">

  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  
  <style>
  li{
    list-style-type: none;
  }

  .jumbotron{
    background-image: url(images/home.png);
    height: 45rem;
    background-repeat: no-repeat;
    background-size: cover;
    background-color: #fff;
    border-radius: 0rem;
  }

  .container{
    color: white;
  }

  .bg-dark{
    background-color: #000000 !important;
  }

  .navbar-light .navbar-nav .nav-link {
    color: #b9b9b9;
  }

  .navbar-nav li{
    margin-right: 3rem;
  }

  .navbar-nav .active{
    text-decoration: underline; 
    color: white;
  }
  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-dark">
    <!-- <a class="navbar-brand" href="#">Navbar</a> -->
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Projects
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <a class="dropdown-item" href="#">Something else here</a>
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Download Resume</a>
        </li>
      </ul>
    </div>
  </nav>

<div class="jumbotron">
    <div class="container text-center">
      <h1 class="mb-5">Hi, I am Sakina Das</h1>    
      <h5>a creative being from Seattle, WA</h5>  
      <h3 class="mb-5">UI-UX Designer & Frontend Developer.</h3>
      <!-- <img src="images/home.png"> -->
      <!-- <div class="row pt-3">
        <div class="col-md-4">
          <h5>What I CAN do...</h5>
          <ul class="text-left">
            <li>UI UX research</li>
            <li>Wireframing</li>
            <li>Prototyping</li>
            <li> Website design</li>
            <li> UI development</li>
            <li>Frontend testing</li>
            <li>Design enhancements</li>
          </ul>
        </div>
        <div class="col-md-4"><img src="images/home.png" style="border-radius: 10rem;"></div>
        <div class="col-md-4">
            <h5>What I FOCUS on...</h5>
            <ul class="text-left">
              <li>UI design</li>
              <li>UI development</li>
              <li>HTML, CSS, JavaScript</li>
              <li> Bootstrap, SCSS</li>
            </ul>
          </div>
      </div> -->

    </div>
  </div>
    

  <div class="container-fluid text-center">    
    <h2 class="pt-4 pb-4 bg-dark">Some of my Work</h2 class="mb-3"><br>
    <div class="row">
      <div class="col-sm-4 project">
        <p>Some text..</p>
        <img src="projects/ProjectT-mobile/t-mobile-promo.png" class="img-responsive" style="width:100%" alt="Image">
        <button class="btn">View Project</button>
      </div>
      <div class="col-sm-4 project"> 
        <p>Some text..</p>
        <img src="projects/ProjectAEM/thumb.png" class="img-responsive" style="width:100%" alt="Image">
        <a href="msftaem.html"><button class="btn">View Project</button></a>
      </div>
      <div class="col-sm-4 project"> 
        <p>Some text..</p>
        <img src="projects/ProjectBlogSite/blog-price2.png" class="img-responsive" style="width:100%" alt="Image">
        <button class="btn"><a href="msftaem.html">View Project</a></button>
      </div>

    </div>
  </div><br>
  
  <div class="container-fluid text-center">    
    <div class="row">
        <div class="col-sm-4 project"> 
            <p>Some text..</p>
            <img src="projects/ProjectLegwork/login.png" class="img-responsive" style="width:100%" alt="Image">
            <button class="btn"><a href="legworkcase.html">View Project </a></button> 
        </div>
      <div class="col-sm-4 project"> 
        <p>Some text..</p>
        <img src="projects/ProjectHealth-app/thumb.png" class="img-responsive" style="width:100%" alt="Image">
        <button class="btn">View Project</button> 
      </div>
      <div class="col-sm-4 project"> 
          <p>Some text..</p>
          <img src="projects/ProjectGoSmile/thumb.png" class="img-responsive" style="width:100%" alt="Image">
          <button class="btn"><a href="legworkcase.html">View Project </a></button> 
        </div>
    </div>
  </div><br><br>
  
  <footer class="container-fluid text-center">
    <p>Footer Text</p>
  </footer>
  
</body>
</html>
