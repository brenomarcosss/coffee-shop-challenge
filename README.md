# coffee-shop-challenge
Coffee Shop project we'll build and style a drinks and snacks menu for a local coffee shop.


That is our **HTML code ** for our menu: 


<!doctype html>
<html>
  <head>
    <link rel="stylesheet" href="style.css">
    <title>Coffee Shop Menu</title>
  </head>
  <body>
    <div class="header">
      <h1>Bean & Brew Cafe</h1>
      <p>Discover our slection of drinks and snacks</p>
    </div>
    <div>
      <img src="https://mimo.app/i/gray-coffee-maker.png" class="coffee-image">
      <ul class="menu-list">
        <li class="menu-item">Espresso</li>
        <li class="menu-item">Cappuccino</li>
        <li class="menu-item">Latte</li>
        <li class="menu-item">Croissant</li>
        <li class="menu-item">Blueberry Muffin</li>
        <li class="menu-item">Matcha Cookie</li>
      </ul>
    </div>
  </body>
</html>

That is our CSS code to style our coffee menu: 

.header {
  text-align: center;
  color: #5A2D0C;
  background-color: #FFEBCD;
  padding: 20px;
  font-weight: bold;
}

.menu-list {
  background-color: #E6E6FA;
  padding: 20px;
}

.menu-item {
  display: block;
  font-size: 18px;
  color: #333;
}

body {
  font-family: 'Helvetica', sans-serif;
}

.coffee-image {
  position: relative;
  z-index: 2;
  float: right;
  margin-right: 20px;
  margin-top: 15px;
  width: 100px;
}

Final result: https://b1hj60.mimo.run/index.html
