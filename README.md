<!doctype html>
<html lang="en">

<head>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css"
        integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn" crossorigin="anonymous">

    <style>
        body {
            background-color: #000;
            scroll-behavior: smooth;
        }
    </style>


    <title>web design</title>
</head>

<body>

    <!-- Nav-bar  -->
   <div class="container-fluid">
       <div class="row">
           <div class="col-md-12 col-sm-12">

               <nav class="navbar navbar-expand-lg navbar-dark " style="margin-bottom: 0px; background: #000;">
                <a class="navbar-brand" href="#"> <img src="images/logo2.jpeg" alt="logo"
                    style="margin-right: 1px; height: 40px;width:40px;"> <strong> ROBOTICZ</strong></a>
                    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                    aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#about">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Specifications</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Evolution</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                        data-toggle="dropdown" aria-expanded="false">
                        More
                    </a>
                    <div class="dropdown-menu text-light" style="background-color:black; "
                        aria-labelledby="navbarDropdown">
                        <a class="dropdown-item text-light" href="#">Types of Robots</a>
                        <a class="dropdown-item text-light" href="#">Upcoming Technalogy</a>
                        <div class="dropdown-divider"></div>
                        <a class="dropdown-item text-light" data-toggle="modal" data-target="#exampleModal"
                            data-whatever="@mdo">Submit Your Opinion</a>
                    </div>
                </li>

            </ul>
            <ul class="nav nav-pills">
                <li class="nav-item">
                    <a class="nav-link active" href="#">Contact Us</a>
                </li>
            </ul>
        </div>
    </div>
</nav>
    </div>
</div>

    <!-- background image -->
<div class="container-fluid">
    <div class="row">
        <div class="col-md-12">

            <div class="p-3 mb-2  text-dark container-fluid" style="margin-top: 0; margin-bottom: 0%; background-color: black;">
                <img src="images/slider2.webp" style="height: 100%; width: 100%; margin: 0px;" alt="...">
            </div>
        </div>
    </div>
</div>




    <!-- about-section -->
    <div class="container-fluid" id="about" style="margin-top: 100px; background-color:black;">
  
        <div class="container-md text-light">
            
            <h1 style="margin-left: ; font-size:150%; text-transform: capitalize;"><strong>WHAT IS ROBOTICS ?</strong></h1>
            </div>

        <div class="image container-md float-left" style="margin-top: ; margin-right:;">
            <img src="images/about.jpg" class="rounded float-left" alt="..." style="height: 50%; width: 50%; ">
            
                <div class="container-md text-light" style="text-transform: capitalize;">
                    <p><b><span style="font-size: 20px;">Robotics</span></b> is an interdisciplinary sector of science
                        and engineering dedicated to the design, construction and use of mechanical robots. </p><p> Our guide
                        will give you a concrete grasp of robotics, including different types of robots and how they're
                        being applied across industries.</p>
                        <p>As technology progresses, so too does the scope of what is considered robotics. In 2005, 90% of
                            all robots could be found assembling cars in automotive factories. Today, we’re seeing an
                            evolved and expanded definition of robotics that includes the development, creation and use of
                            bots that explore Earth’s harshest conditions, robots that assist law-enforcement and even
                            robots that assist in almost every facet of healthcare. </p>
                        </div>
                    
                </div>
            </div>
    

 <!-- evolution-->
 <div class="container-fluid" style="margin-top: 100px; background-color:black;">
  

    <div class="container float-center">
        <img src="images/evolutiown.jpg" class="rounded float-left" alt="..." style="height: 100%; width: 100%; margin-top: 200px; ">
        </div> 
</div>
    <!-- opinion form -->

    <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header bg-dark text-light">
                    <h5 class="modal-title" id="exampleModalLabel">Your Opinion</h5>
                    <button type="button" class="close text-light" data-dismiss="modal" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>
                </div>
                <div class="modal-body">
                    <form>
                        <div class="form-group">
                            <label for="recipient-name" class="col-form-label">Your Email:</label>
                            <input type="text" class="form-control" id="recipient-name">
                        </div>
                        <div class="form-group">
                            <label for="message-text" class="col-form-label">Message:</label>
                            <textarea class="form-control" id="message-text"></textarea>
                        </div>
                    </form>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary">Send message</button>
                </div>
            </div>
        </div>
    </div>






    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js"
        integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-fQybjgWLrvvRgtW6bFlB7jaZrFsaBXjsOMm/tB9LTS58ONXgqbR9W8oWht/amnpF"
        crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.min.js" integrity="sha384-VHvPCCyXqtD5DqJeNxl2dtTyhF78xXNXdkwX1CZeRusQfRKp+tA7hAShOK/B/fQ2" crossorigin="anonymous"></script>
    -->
</body>

</html>
