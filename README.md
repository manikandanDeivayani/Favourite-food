# Favourite-food
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Favourite food</title>
    <style>
        #topbar{
            background-color: rgb(16, 130, 184);
            padding: 24px;
        }
        .menu-item{
            font-size: 24px;
            padding: 8px;
            font-weight: 500;
        }
        #list-heading{
            font-size: 20px;
            padding-left: 24px;
        }
        .food-list-item{
            font-size: 20px;

        }
        .food-image
        {
            height: 400px;
            width: 400px;
        }
        .food-wrapper
        {
            text-align: center;
        }
    </style>
</head>
<body style="margin: 0; background-color: lightblue;">
    <div id="topbar">
        <span class="menu-item">Index</span>
        <span class="menu-item">Food</span>
        <span class="menu-item">About</span>
    </div>
     <h3 id="list-heading">Top 5 Favourite food: </h3>
     <ul>
        <li><a class="food-list-item" href="#Biriyani">Biriyani</a></li>
        <li><a class="food-list-item" href="#pizza">pizza</a></li>
        <li><a class="food-list-item" href="#lasagna">lasagna</a></li>
        <li><a class="food-list-item" href="#Burger">Burger</a></li>
        <li><a class="food-list-item" href="#Caesar salad">Caesar salad</a></li>
     </ul>

     <div class="food-wrapper">
        <img id="Biriyani" class="food-image" src="https://thumbs.dreamstime.com/b/hyderabadi-chicken-biryani-38473399.jpg" alt="chicken-biryani">
        <p>Biriyani</p>
     </div>
     <div id="pizza" class="food-wrapper">
        <img class="food-image" src="https://img.onmanorama.com/content/dam/mm/en/food/features/images/2021/10/17/pizza.jpg.transform/schema-16x9/image.jpg" alt="pizza">
        <p>pizza</p>
     </div>
     <div id="lasagna" class="food-wrapper">
        <img class="food-image" src="https://thumbs.dreamstime.com/b/tomato-ground-beef-lasagne-cheese-layered-sheets-traditional-italian-pasta-served-white-plate-dark-64979694.jpg" alt="lasagne">
        <p>lasagna</p>
     </div>
     <div id="Burger" class="food-wrapper">
        <img class="food-image" src="https://media.istockphoto.com/id/1188412964/photo/hamburger-with-cheese-and-french-fries.jpg?s=612x612&w=0&k=20&c=lmJ0qUjC3FtCrWOGU0hWvqBgXcKZ1imiXKOMuHRfFH8=" alt="Burger">
        <p>Burger</p>
     </div>
     <div id="Caesar salad" class="food-wrapper">
        <img class="food-image" src="https://thumbs.dreamstime.com/b/chicken-caesar-salad-delicious-parmesan-cheese-dressing-croutons-115376441.jpg" alt="chicken-caesar-salad-delicious">
        <p>Caesar salad</p>
     </div>
</body>
</html>
