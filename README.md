<!DOCTYPE html>
<html>
<head>
    <title>Food Order Website</title>
    <style>
        /* Global styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Header styles */
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        h1 {
            margin: 0;
        }

        /* Main content styles */
        main {
            padding: 40px;
        }

        h2 {
            margin-bottom: 20px;
        }

        p {
            text-align: justify;
            line-height: 1.5;
        }

        /* Featured dishes section styles */
        .featured-dishes {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            margin-top: 40px;
        }

        .dish {
            width: calc(33.33% - 20px);
            margin-bottom: 40px;
            padding: 20px;
            border: 1px solid #ccc;
            text-align: center;
        }

        .dish img {
            width: 100%;
            max-height: 200px;
            object-fit: cover;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        /* Order now button styles */
        .order-btn {
            display: block;
            margin: 40px auto;
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
            text-decoration: none;
            border-radius: 4px;
        }

        /* Footer styles */
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Food Order Website</h1>
    </header>

    <main>
        <h2>Featured Dishes</h2>
        <div class="featured-dishes">
            <div class="dish">
                <img src="C:\Users\bhuva\OneDrive\Desktop\images for websites\chicken.jpg" alt="Dish 1">
                <h3>Dish 1</h3>
                <p>Potluck Macaroni and Cheese</p>
            </div>
            <div class="dish">
                <img src="C:\Users\bhuva\OneDrive\Desktop\images for websites\pasta.jpg" alt="Dish 2">
                <h3>Dish 2</h3>
                <p>Favorite Chicken Potpie</p>
            </div>
            <div class="dish">
                <img src="C:\Users\bhuva\OneDrive\Desktop\images for websites\potpie.jpg" alt="Dish 3">
                <h3>Dish 3</h3>
                <p>Contest-Winning Broccoli Chicken Casserole</p>
            </div>
        </div>

        <a href="#" class="order-btn">Order Now</a>
    </main>

    <footer>
        <p>&copy; 2023 Food Order Website. All rights reserved.</p>
    </footer>
</body>
</html>
