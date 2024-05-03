<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    <link rel="icon" type="image/png" href="favicon.png">
    <title>Apple</title>
    <style>
        .navbar {
            margin: 0 auto;
            width: fit-content;
            font-family: 'San Francisco', Arial, sans-serif;
        }

        .navbar-nav .nav-link {
            font-size: 0.7rem;
            margin-right: 10px;
            margin-left: 10px;
            position: relative; /* Para permitir posicionamento absoluto */
        }

        .dropdown-menu {
            display: none;
            position: absolute;
            background-color: #f0f0f0;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
            z-index: 1;
            width: auto;
            min-width: 200px;
            max-width: 600px; 
            padding: 10px; 
            box-sizing: border-box; 
            top: calc(100% + 5px); 
            left: 0; 
        }

        .nav-link:hover + .dropdown-menu {
            display: block; 
        }

        .dropdown-item {
            display: block;
            padding: 10px 20px;
            color: #333;
            text-decoration: none; 
            transition: background-color 0.3s; 
            white-space: nowrap; 
        }

        .dropdown-item:hover {
            background-color: #f0f0f0;
        }

        .titulo {
            padding-left: 220px;
            position: relative;
            top: 100px;
        }

        .colorido {
            color: #696969;
        }

        .subtittle {
            padding-left: 800px;
            position: relative;
            top: 30px;
        }

        .row {
            position: absolute;
            top: 350px;
            left: 350px;
        }

       
        .custom-img {
        width: auto;
        height: auto;
        max-width: 150px;
        max-height: 150px;
        border: none;
        transition: transform 0.3s ease, box-shadow 0.3s ease; 
        }

    .custom-img:hover {
        transform: scale(1.1);
        box-shadow: 0 8px 35px rgba(0, 0, 0, 0.2); 
        }

        .new {
            position: absolute; 
            top: 600px; 
            left: 40%; 
            transform: translateX(-50%);}
            
            #carouselExampleAutoplaying {
        max-width: 800px;
        margin: auto; 
        top: 420px; 
        left: 10px; 
    }

    #carouselExampleAutoplaying img {
        max-width: 100%; 
        max-height: 400px; 
        object-fit: cover; 
        border: 1px solid #ddd; 
        box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); 
        border-radius: 8px;
        overflow: hidden; 
        transition: box-shadow 0.5s ease;
    }
    #carouselExampleAutoplaying:hover {
        
        box-shadow: 0 8px 30px rgba(0, 0, 0, 0.2);}
        
        
    .carousel-caption {
        top: 90.1%; 
        transform: translateY(-50%); 
        padding: 20px;}
        
        #carouselExampleAutoplaying .carousel-item:nth-child(1) .carousel-caption {
        color: rgb(255, 255, 255); 
    }

   
    #carouselExampleAutoplaying .carousel-item:nth-child(2) .carousel-caption {
        color: rgb(0, 0, 0); 
    }

   
    #carouselExampleAutoplaying .carousel-item:nth-child(3) .carousel-caption {
        color: rgb(0, 0, 0); /
    }
    #carouselExampleAutoplaying .carousel-item:nth-child(4) .carousel-caption {
        color: rgb(0, 0, 0); /
    }
    .form-container {
            position: relative; 
            top: 530px; 
            left: 125%; 
            transform: translateX(-50%);
        }

        .mb-3 {
            width: 300px; 
            background-color: #ffffff; 
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease; 
        }
        .mb-3:hover {
        transform: scale(1.1);
        box-shadow: 0 8px 35px rgba(0, 0, 0, 0.2); 
        }
        .custom-h2 {
        position: absolute;
        top: 180%; 
        left: 15%; }
        
        .card {
    width: 18rem;
    background-color: #ffffff;
    padding: 20px;
    border-radius: 10px;
    transition: transform 0.3s ease; /* Removida a transição da box-shadow */
    overflow: hidden; 
    margin-bottom: 20px;
    outline: none; /* Remove qualquer contorno */
}

.card:hover {
    transform: scale(1.1);
    box-shadow: 0 8px 35px rgba(0, 0, 0, 0.2);
}




    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">
                <i class="fa-brands fa-apple"></i>
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                    <a class="nav-link" href="#">Loja</a>
                    <div class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMac" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Mac
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownMac">
                            <a class="dropdown-item" href="#">MacBook</a>
                            <a class="dropdown-item" href="#">MacBook Air</a>
                            <a class="dropdown-item" href="#">MacBook Pro</a>
                        </div>
                    </div>
                    <div class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownIpad" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            iPad
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownIpad">
                            <a class="dropdown-item" href="#">iPad Pro</a>
                            <a class="dropdown-item" href="#">iPad Air</a>
                            <a class="dropdown-item" href="#">iPad</a>
                        </div>
                    </div>
                    <div class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownIphone" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            iPhone
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownIphone">
                            <a class="dropdown-item" href="#">iPhone 13</a>
                            <a class="dropdown-item" href="#">iPhone 13 Pro</a>
                            <a class="dropdown-item" href="#">iPhone 13 Mini</a>
                        </div>
                    </div>
                    <div class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownWatch" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Watch
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownWatch">
                            <a class="dropdown-item" href="#">Apple Watch Series 7</a>
                            <a class="dropdown-item" href="#">Apple Watch SE</a>
                            <a class="dropdown-item" href="#">Apple Watch Series 3</a>
                        </div>
                    </div>
                    <div class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownAirPods" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            AirPods
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownAirPods">
                            <a class="dropdown-item" href="#">AirPods Pro</a>
                            <a class="dropdown-item" href="#">AirPods Max</a>
                            <a class="dropdown-item" href="#">AirPods</a>
                        </div>
                    </div>
                    <div class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownTV" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            TV e Casa
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownTV">
                            <a class="dropdown-item" href="#">Apple TV 4K</a>
                            <a class="dropdown-item" href="#">HomePod mini</a>
                            <a class="dropdown-item" href="#">Acessórios para TV e Casa</a>
                        </div>
                    </div>
                    <div class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownEntretenimento" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Entretenimento
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownEntretenimento">
                            <a class="dropdown-item" href="#">Apple Music</a>
                            <a class="dropdown-item" href="#">Apple TV+</a>
                            <a class="dropdown-item" href="#">Apple Arcade</a>
                        </div>
                    </div>
                    <div class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownAcessorios" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Acessórios
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownAcessorios">
                            <a class="dropdown-item" href="#">Cases</a>
                            <a class="dropdown-item" href="#">Capas</a>
                            <a class="dropdown-item" href="#">Carregadores</a>
                        </div>
                    </div>
                    <a class="nav-link" href="#">Suporte</a>
                    <a class="nav-link" href="#">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </a>
                    <a class="nav-link" href="#">
                        <i class="fa-solid fa-bag-shopping"></i>
                    </a>
                </div>
            </div>
        </div>
    </nav>
    
    
    <div class="container">
        <div class="titulo">
          <h1>Bem-vindo<br>
            <span class="colorido">à Loja da Apple.</span>
          </h1>
        </div>
        <div class="subtittle"> 
          <h6 class="fw-bold"><i class="fab fa-apple"></i> Visite uma Apple Store</h6>
          <p><a href="https://exemplo.com">Procure uma loja perto de você > </a></p>
        </div> 
      </div>

     <div class="container">
        <div class="row">
            <div class="col-md-3 text-center">
                <div class="d-inline-block position-relative">
                    <img src="mac.jpg" class="img-thumbnail custom-img d-inline">
                </div>
                <p><strong>Macbook</strong></p>
            </div>
            <div class="col-md-3 text-center">
                <div class="d-inline-block position-relative">
                    <img src="iphone.jpg" class="img-thumbnail custom-img d-inline">
                </div>
                <p><strong>Iphone</strong></p>
            </div>
            <div class="col-md-3 text-center">
                <div class="d-inline-block position-relative">
                    <img src="ipad.jpg" class="img-thumbnail custom-img d-inline">                    
                </div>
                <p><strong>Ipad</strong></p>
            </div>
            <div class="col-md-3 text-center">
                <div class="d-inline-block position-relative">
                    <img src="airpods.jpg" class="img-thumbnail custom-img d-inline">
                </div>
                <p><strong>AirPods</strong></p>
            </div>
        </div>
    </div>
    <h2 class="new">
        O mais recente.
        <small class="text-body-secondary">Dê uma olhada no que há de novo agora.</small>
      </h2>
      
      <div id="carouselExampleAutoplaying" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="iphone15.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>IPHONE 15 PRO</h5>
              <p>A partir de $999 ou %41/mês por 24 meses.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="applevision.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>APPLE VISION PRO</h5>
              <p>A partir de $3.499 ou $291/mês por 12 meses.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="macb.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>MACBOOK AIR</h5>
              <p>A partir de $999 ou $83/mês por 12 meses.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="ultrarelo.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>APPLE RELÓGIO ULTRA 2</h5>
              <p>A partir de $799 ou $66/ mês por 12 meses</p>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      
      <div class="form-container">
        <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label">Email</label>
            <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
        </div>
        <div class="mb-3">
            <label for="exampleFormControlTextarea1" class="form-label">Dê seu feedback</label>
            <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
        </div>
    </div>
    
    <h2 class="custom-h2" style="font-family: 'San Francisco', Arial, sans-serif; font-size: 35px; color: #F54536;">
        <strong>A diferença da Apple Store.</strong><br>
        <small class="text-body-secondary"><strong>Ainda mais motivos para comprar conosco.</strong></small>
    </h2>
    

    <div class="card" style="width: 18rem; position: absolute; top: 200%; left: 200px;">
        <div class="card-body">
            <i class="fa-solid fa-bus-simple" style="color: #D93D86;"></i>
            <p class="card-text" style="font-family: 'San Francisco', Arial, sans-serif; color:#D93D86"><strong>a entrega em
                duas horas em uma<br>
                Apple Store, entrega<br>
                gratuita ou retirada<br>
                fácil.</strong></p>
        </div>
    </div>
    <div class="card" style="width: 18rem; position: absolute; top: 236%; left: 200px;">
        <div class="card-body" style="font-family: 'San Francisco', Arial, sans-serif; color:#F27141">
            <i class="fa-solid fa-credit-card" style="color: #F27141;"></i>
            <p class="card-text"><strong>Pague integralmente<br>
                ou pague no prazo. Sua<br>
                escolha</strong><br></p>
        </div>
    </div>
    <div class="card" style="width: 18rem; position: absolute; top: 265%; left: 200px;">
        <div class="card-body" style="font-family: 'San Francisco', Arial, sans-serif; color:#F54536">
            <i class="fa-solid fa-computer" style="color: #F54536;"></i>
            <p class="card-text"><strong>Personalize o seu Mac<br>
                com chip, memória,<br>
                armazenamento e cor<br></strong><br> </p>
        </div>
    </div>
    
    <div class="card" style="width: 18rem; position: absolute; top: 200%; left: 555px;">
        <img src="chicken.gif" class="card-img-top" alt="...">
        <p class="card-text"><strong>MEMOJI™</strong></p>
        <div class="card-body">
        </div>
    </div>
    <div class="card" style="width: 18rem; position: absolute; top: 245%; left: 555px;">
        <img src="dragon.gif" class="card-img-top" alt="...">
        <p class="card-text"><strong>MEMOJI™<br>
            Os Memoji são avatares animados<br>
             que podem refletir suas as características<br>
             faciais e personalidade<br>
        </strong></p>
        <div class="card-body">
        </div>
    </div>
    <a class="nav-link" style="width: 18rem; position: absolute; top: 245%; left: 1000px;" href="#">
        <i class="fab fa-facebook"></i>
    </a>
    <a class="nav-link" style="width: 18rem; position: absolute; top: 245%; left: 1050px;" href="#">
        <i class="fab fa-twitter"></i>
    </a>
    <a class="nav-link" style="width: 18rem; position: absolute; top: 245%; left: 1100px;" href="#">
        <i class="fab fa-instagram"></i>
    </a>
    

      <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

      

    </body>
</html>
