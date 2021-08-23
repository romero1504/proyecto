<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

</head>

<body>
    <nav class="navbar navbar-light" style="background-color: #F73535;">
        <ul class="nav justify-content-start">
            <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#"><img
                        src="./img/arrow_back_ios_black_24dp.svg"></a>
            </li>
        </ul>
        <ul class="nav justify-content-end">
            <li class="nav-item">
                <a class="nav-link" href="#"><img src="./img/search_black_24dp.svg"></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#"><img src="./img/account_circle_black_24dp.svg"></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#"><img src="./img/print_black_24dp.svg"></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#"><img src="./img/paid_black_24dp.svg"></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#"><img src="./img/more_vert_black_24dp.svg"></a>
            </li>
        </ul>
    </nav>
    <nav class="navbar navbar-light" style="background-color: #3D3D3D;">
        <div class="dropdown">
            <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton1" data-bs-toggle="dropdown" aria-expanded="false">
                Ordenes a Adomicilio
            </button>
            <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
              <li><a class="dropdown-item" href="#">Salon Principal</a></li>
              <li><a class="dropdown-item" href="#">Ordenes para Llevar</a></li>
              <li><a class="dropdown-item" href="#">Ordenes a Adomicilio</a></li>
            </ul>
          </div>
    </nav>
    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="./img/comida-sudamerica.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>Promocion</h5>
              <p>2x1</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="./img/1487689958_197792_1487690084_noticia_normal.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>Promocion</h5>
              <p>Gasta 15mil y el envio es gratis</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="./img/ingredientes-pizza-queso-peperoni-destacado-axion1.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>Promocion</h5>
              <p>Regalia de refresco/p>
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
      <div class="card" style="width: 18rem;">
        <img src="./img/muslos-de-pollo-portada-3.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Platos con Pollo</h5>
          <p class="card-text">Variedad de pollo asado, a la plancha, frito, etc...</p>
          <a href="#" class="btn btn-primary">Ordener</a>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img src="./img/ensalada-griega.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Ensaladas</h5>
          <p class="card-text">Variedad de ensaladas, posibilidad de armar la ensalada a tu gusto.</p>
          <a href="#" class="btn btn-primary">Ordenar</a>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img src="./img/hamburguesa-2028707.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Hamburgesas</h5>
          <p class="card-text">Arma tu hamburgesa al gusto</p>
          <a href="#" class="btn btn-primary">Ordenar</a>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img src="./img/Rice-Pizza-Crust.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Pizza</h5>
          <p class="card-text">Promocion esclusiva para esta semana</p>
          <a href="#" class="btn btn-primary">Ordenar</a>
        </div>
      </div>

</body>

</html>