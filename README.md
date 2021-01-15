<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style2.css">

<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+SC:wght@400;500&display=swap" rel="stylesheet">

<head/>
<body>
  <header class = 'header'>
    <div class = 'container'>
      <nav class = 'nav'>
        <img src="img/logo.svg"  width="473" height="102" alt="TOP SHOES" class = 'logo'>
        <ul class = 'menu'>
          <li >
             <a href="#">Главная</a>
          </li>
          <li>
             <a href="#">О магазине</a>
          </li>
          <li>
             <a href="#">Контакты</a>
          </li>

        </ul>
        <div class = 'korzina'>
          <img src="img/korzina.svg"  alt="TOP SHOES">
        </div>
      </nav>
      <div class="offer">
        <div class = 'offer-content'>
          <h1>
            Обувь на <br> любой вкус
          </h1>
          <p>
            Найди себе пару  не<br>  выходя из дома
          </p>
         <a href="#">Каталог</a>
        </div>
        <div class="flex-wrapper">
    <div class="slider-wrapper">
      <div class="slide actives ">
        <img src="img/img1.png">
      </div>
      <div class="slide ">
        <img src="img/img2.png">
      </div>
      <div class="slide">
        <img src="img/img3.png">
      </div>
      <div id="btn-prev"></div>
      <div id="btn-next"></div>
    </div>  
  </div>
  <div class="dots-wrapper">
    <span class="dot actived"></span>
    <span class="dot"></span>
    <span class="dot"></span>   
  </div>
          
        </div>
      </div>  

    </div>

  </header>
  <script src="slide.js"></script>
</body>
</html>
