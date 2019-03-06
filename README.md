<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Project 101</title>
    <link rel="stylesheet" href="bootstrap/css/bootstrap.css">
    <link rel="stylesheet" href="bootstrap/fonts/css/all.css">

</head>
<body>

<!--navbar-->
<nav class="navbar navbar-expand-md navbar-light bg-blue fixed-top" >

    <a href="#" class="navbar-brand"><i class="fas fa-gamepad text-warning fa-2x"></i></a>

    <button type="button" class="navbar-toggler bg-light " data-toggle="collapse" data-target="#nav" ><span class="navbar-toggler-icon"></span></button>

    <div class="collapse navbar-collapse justify-content-between" id="nav">
        <ul class="navbar-nav">
        <li class="nav-item">
            <a class="nav-link text-danger text-uppercase font-weight-bold px-3" href="#home">Home</a>
        </li>
        <li class="nav-item">
            <a class="nav-link text-dark text-uppercase font-weight-bold px-3" href="#about">About us</a>
        </li>
        <li class="nav-item">
            <a class="nav-link text-dark text-uppercase font-weight-bold px-3" href="#contact">Contact us</a>
        </li>

            <li class="nav-item">
                <a class="nav-link text-dark text-uppercase font-weight-bold px-3" href="#gallery">gallery</a>
            </li>


    </ul>
    </div>
</nav>
<!--end of navbar-->

<!--banner-->
<section id="home">
    <div class="container-fluid">
        <div class="row bg-success justify-content-center align-items-center" style="height: 100vh">
        <div class="col-sm-10 text-center">
        <h1 class="display-2 text-capitalize"><span class="text-warning">project101</span><span class="text-light font-weight-bolder">Website</span>
        </h1>
            <h2 class="font-weight-light font-italic text-light">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab accusantium, alias at cumque delectus dolores ducimus ea error eum fuga hic in iste laborum, maxime odio officia sunt ullam ut?</h2>
                  <!--<button class="btn btn-outline-warning" data-toggle="modal" data-target="#myModal">Register with us </button>-->
<button class="btn btn-outline-warning" data-toggle="modal" data-target="#newmodal"> Reg</button>

        </div>
        </div>
    </div>
</section>
<!--end of banner-->


<br>
<br>
<div class="md-3">
   <section>
    <!--carousel-->
    <div class="container-fluid j" id="gallery" >
        <div id="demo" class="carousel slide" data-ride="carousel">
            <ul class="carousel-indicators">
                <li data-target="#demo" data-slide-to="0" class="active"></li>
                <li data-target="#demo" data-slide-to="1"></li>
                <li data-target="#demo" data-slide-to="2"></li>

            </ul>
            <div class="jumbotron">
                <h1 class="text-center text-warning display-2">GALLERY</h1>
                <br>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="images/images2.jpg" alt="nature01"  style="width: 1100px;height: 500px" >
                        <div class="carousel-caption">
                            <h3 class="text-center">pleasant site to see</h3>
                            <p class="text-center">We had such a great time in in this wonderful place!</p>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <img src="images/waterfall.jpg" alt="nature02" style="width: 1100px;height: 500px" >
                        <div class="carousel-caption">
                            <h3 class="text-center">Waterfall</h3>
                            <p class="text-center">Thank you, Chicago!</p>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <img src="images/images.jpg" alt="nature03"  style="width: 1100px;height: 500px">
                        <div class="carousel-caption">
                            <h3 class="text-center">breathtaking</h3>
                            <p class="text-center">We love the place very much!</p>
                        </div>
                    </div>
                </div>
                <a class="carousel-control-prev" href="#demo" data-slide="prev">
                    <span class="carousel-control-prev-icon"></span>
                </a>
                <a class="carousel-control-next" href="#demo" data-slide="next">
                    <span class="carousel-control-next-icon"></span>
                </a>
            </div>
        </div>

    </div>
       <!--end of carousel-->
   </section>

    <section id="about" >

        <h2 class="text-center text-warning text-uppercase display-2">about us</h2>
    <div class="row " >

                    <div class="col-6">
            <img src="images/NATURE+GENERIC+TREES.jpg" alt="" style="width: 500px;height: 400px"   >
    <p class="text-center">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid consectetur eum id nesciunt pariatur quae veritatis vitae? Beatae, blanditiis, cumque dolorem, et mollitia necessitatibus porro quasi sapiente ut veniam voluptatem!</p>
            </div>

            <div class="col-6">
                <img src="images/waterfall.jpg" alt="" style="width: 500px;height: 400px">
    <p class="text-center">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid consectetur eum id nesciunt pariatur quae veritatis vitae? Beatae, blanditiis, cumque dolorem, et mollitia necessitatibus porro quasi sapiente ut veniam voluptatem!</p>
        </div>

    </div>

</section>
</div>
<!--the modal-->
<div class="modal" id="myModal">
    <div class="modal-dialog">
        <div class="modal-content">

            <!--modal body-->
            <div class="modal-body">

                <div class="container">
                    <div class="form-group">
                        <label for="name">Name:</label>
                        <input type="text" class="form-control " id="name" name="name">
                        <label for="id number">ID Number:</label>
                        <input type="number" class="form-control" id="id number" name="id number">
                        <label for="email">email address</label>
                        <input type="email" class="form-control" id="email" name="date picked">
                        <label>attach photo</label>
                        <input type="file" class="form-control-file">
                        <button class="btn btn-success">submit</button>

                    </div>

                </div>

            </div>
        </div>
    </div>
</div>

<section class="p-5 bg-light" ID="contact">
    <div class="row">
        <div class="col text-center mb-3">
            <h2 class="text-warning display-2">ContactUs</h2>
        </div>
    </div>

    <div class=" row justify-content-center">
    <div class="col-lg-6 col-md-8 col-sm-10">
        <div class="text-center text-secondary">
            <h2>Got Question?</h2>
            <p>Stay Connected</p>
        </div>
        <form class="text-muted">
            <div class="form-group">
                <label for="nm">Name</label>
                <input type="text" id="nm" >

            </div>
            <div class="form-group">
                <label for="eml">Email</label>
                <input type="email" id="eml" >

            </div>
            <div class="form-group">
                <label for="message">Message</label>
                <textarea class="form-control" id="message" rows="3"></textarea>

            </div>
            <button class="btn btn-outline-warning btn block "type="submit">Submit Question</button>
        </form>

    </div>
    </div>

</section>
<!--end of contact-->
<!--footer-->
<footer class="bg-secondary">
    <div class="container">
        <div class="row">
            <div  class="col text-center">
                <h1 class="text-white font-weight-light text-capitalize p-3">project101 website</h1>
                <h3 class="text-light font-weight-light font-italic mb3">this is my assignment</h3>
            <div class="py-2">
                <a href="#"><i class="fab fa-facebook fa-2x text-primary mx-3"></i></a>
                <a href="#"><i class="fab fa-google fa-2x text-danger mx-3"></i></a>
                <a href="#"><i class="fab fa-twitter fa-2x text-info mx-3"></i></a>
                <a href="#"><i class="fab fa-youtube fa-2x text-danger mx-3"></i></a>
            </div>
                <p class="text-light py-4 m-0">&copy;Copyright 2018 - Made by DanielGacheru</p>
            </div>

        </div>
    </div>

</footer>
<!--end of footer-->
<script src="bootstrap/js/popper.min.js"></script>
<script src="bootstrap/js/bootstrap.js"></script>
<script src="bootstrap/js/jquery.js"></script>
</body>
</html>
