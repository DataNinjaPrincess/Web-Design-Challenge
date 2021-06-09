<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Latitude Study</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="index.html">Latitude</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Plots</a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="CloudCover.html">Cloud Cover</a>
              <a class="dropdown-item" href="Humidity.html">Humidity</a>
              <a class="dropdown-item" href="Temperature.html">Temperature</a>
              <a class="dropdown-item" href="WindSpeed.html">Wind Speed</a>
            </div>        
        </li>
        <li class="nav-item">
          <a class="nav-link" href="Comparison.html">Comparison</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="Data.html">Data</a>
        </li>
      </ul>
    </div>
  </nav>

  <div class="container">
    <div class="jumbotron">
      <h1 class = "jumbotron">Summary: Impact of Latitude on Various Factors</h1>
      <hr>
      <p class="lead">This is placed inside a container</p>

    </div>
  </div>

<div class="container">
  <h3 class="text-center">Visualizations</h3>
    <div class="row">
        <div class="col-md-3">
          <div class="thumbnail">
            <img src="Visualizations/LatitudeVsCloudCover.png" class="img-thumbnail">
          </div>
          <div class="caption">
              <h5>Latitude vs Cloud Cover</h5>
          </div>
        </div>  
        <div class="col-md-3">
            <div class="thumbnail">
              <img src="Visualizations/LatitudeVsHumidity.png" class="img-thumbnail">
            </div>
            <div class="caption">
                <h5>Latitude vs Humidty</h5>
            </div>
        </div>    
        <div class="col-md-3">
          <div class="thumbnail">
            <img src="Visualizations/LatitudeVsMaxTemp.png" class="img-thumbnail">
          </div>
          <div class="caption">
              <h5>Latitude vs Maximum Temperature</h5>
          </div>
        </div>      
        <div class="col-md-3">
          <div class="thumbnail">
            <img src="Visualizations/LatitudeVsWindSpeed.png" class="img-thumbnail">
          </div>
          <div class="caption">
              <h5>Latitude vs Wind Speed</h5>
          </div>
        </div>
    </div>

</div>
</body>
