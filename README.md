<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta http-equiv="X-UA-Compatible" content="IE=edge">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <link rel="stylesheet" href="style.css">
 <title>Weather App</title>
</head>
<body>
 <div class="card">
  <div class="search">
   <input type="text" class="search-bar" placeholder="Search">
   <button><svg stroke="currentColor" fill="currentColor" stroke-width="0" viewBox="0 0 16 16" height="1.5em" width="1.5em" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.442 10.442a1 1 0 011.415 0l3.85 3.85a1 1 0 01-1.414 1.415l-3.85-3.85a1 1 0 010-1.415z" clip-rule="evenodd"></path><path fill-rule="evenodd" d="M6.5 12a5.5 5.5 0 100-11 5.5 5.5 0 000 11zM13 6.5a6.5 6.5 0 11-13 0 6.5 6.5 0 0113 0z" clip-rule="evenodd"></path></svg></button>
  </div>

  <div class="weather loading">
   <h1 class="city">Weather in Lagos</h1>
   <h1 class="temp">51°C</h1>
   <div class="flex">
    <img src="//cdn.weatherapi.com/weather/64x64/day/116.png" alt="" class="icon">
    <div class="description">Cloudy</div>
   </div>
   <div class="humidity">Humidity:60%</div>
   <div class="wind">Wind Speed:6.2 km/hr</div>
  </div>
 </div>
 <script src="script.js"></script>

</body>
</html>
