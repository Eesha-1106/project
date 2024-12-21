# Project Responsive Web Design using Bootstrap
# Date:7-12-24
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
project.html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel World</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</head>
<body class="bg-ligth">
  
    <nav class="navbar navbar-expand-lg  bg-dark  fixed-top border-bottom border-body "data-bs-theme="dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#brand">Trip Trastic</a>
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <a class="nav-link active" href="#home">Home</a>
                <a class="nav-link active" href="#explore">Explore</a>
                <a class="nav-link active" href="#contact">Contact</a>
            </ul>
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
          </div>
        </div>
      </nav>

      <div  id="home" id="carouselExampleFade" class="carousel slide carousel-fade">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
          </div>
        <div class="carousel-inner">
          <div class="carousel-item active" >
            <img src="C:\Users\admin\Documents\html\project web\imag new.png" class="d-block w-100 h-auto" >
           
            <div class="carousel-caption ">
              <h3 style="font-family: Georgia, 'Times New Roman', Times, serif;">-----Wander The Wonder-----</h3>
                <p >Explore The Nature, admiring it !!!.</p>
              </div>
          </div>
          <div class="carousel-item">
            <img src="C:\Users\admin\Documents\html\project web\img1.jpg" class="d-block w-100 h-32rem" >
            <div class="carousel-caption ">
                <p>the beauty of sound of falls!!!</p>
                
              </div>
          </div>
          <div class="carousel-item">
            <img src="C:\Users\admin\Documents\html\project web\img3.jpg" class="d-block w-100 h-auto" >
            <div class="carousel-caption d-none d-md-block">
                <p>The Nature's Music ,The Calmness Inherited!!!</p>
              </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" ></span>
          
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
          <span class="carousel-control-next-icon" ></span>
          
        </button>
      </div>
    <div id="explore">
      <h1 class="title" style="font-family:Georgia, 'Times New Roman', Times, serif;">---Explore The beauty---</h1>
      <div class="container ">
        <div class="row">
            <div class="col-md-4">

                <div   class="card h-100" style="width:22rem;">
    
                    <img src="C:\Users\admin\Documents\html\project web\coorg.jpg" class="card-img-top ">
                    <div class="card-body">
                        <h2 style="font-family:Georgia, 'Times New Roman', Times, serif;">Coorg</h2>
                       <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                       <a href="#html" class="btn btn-primary">Expore</a>
                    </div>
               </div>
            </div>
            <div class="col-md-4">
                <div   class="card h-100" style="width:22rem;">
    
                   <img src="C:\Users\admin\Documents\html\project web\tpkg-manalitour.jpg" class="card-img-top ">
                   <div class="card-body">
                      <h2 style="font-family:Georgia, 'Times New Roman', Times, serif;">Manali</h2>
                      <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                      <a href="#html" class="btn btn-primary">Explore</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div   class="card h-100" style="width:22rem;">
                   <img src="C:\Users\admin\Documents\html\project web\img2.jpg" class="card-img-top">
                   <div class="card-body">
                    <h2 style="font-family:Georgia, 'Times New Roman', Times, serif;" >Hallstatt</h2>
                     <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                     <a href="#html" class="btn btn-primary">Explore</a>
                    </div>
                </div>
            </div>
      </div>
    </div>
    <div id="contact" class="contacting">
        <h1 class="title1" style="font-family: Georgia, 'Times New Roman', Times, serif;">---Contact us---</h1>
        <p style="text-align:center;padding-left: 20px;">To travel the beauty and know about it contact us your query </p>
        <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label" >Name:</label>
            <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name">
          </div>
          <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label" >Email address:</label>
            <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
          </div>
        <div class="mb-3">
            <label for="exampleFormControlTextarea1" class="form-label" >Your query:</label>
            <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
        </div>
        <button type="button" class="btn btn-warning">Send query</button>
    </div>
    <footer class="bg-dark text-white text-center py-3">
        <p>Eesha Ranka register no:212224240040</p>
    </footer>
</body>
</html>

style.css:
  
        .carousel-item{
            height: 37rem;
        }
        .title{
            padding-top:70px;
            padding-left: 20px;
            padding-bottom: 40px;
            text-align: center;
            
        }
        .title1{
            padding-top:50px;
            padding-left: 20px;
            text-align: center;
            
        }
        .contacting{
            padding:50px;
        }
```
# OUTPUT:
![project home](https://github.com/user-attachments/assets/332a49cd-9600-4383-a1f5-3f1ff28ff5a0)
![explore final](https://github.com/user-attachments/assets/b8dec06a-1b37-4736-b3f9-62d164e8e8c3)
![project contact](https://github.com/user-attachments/assets/b815bf27-4b1f-4969-8613-2e3859de0f2d)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
