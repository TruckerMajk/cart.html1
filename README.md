<!DOCTYPE html>
<html lang="sl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Košarica</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .product {
            border: 1px solid #ccc;
            padding: 10px;
            margin: 10px 0;
        }
        .product-image {
            max-width: 100%;
            height: auto;
        }
        .cart-header {
            position: fixed;
            top: 10px;
            right: 10px;
            background-color: #f8f8f8;
            padding: 10px;
            border: 1px solid #ccc;
        }
    </style>
</head>
<body>
    <div class="cart-header">
        <h2>Košarica</h2>
    </div>
    <div class="container">
        <h1>Izdelki v Košarici</h1>
        <div class="product">
            <h3>AIRPODS 4</h3>
            <img src="https://store.storeimages.cdn-apple.com/1/as-images.apple.com/is/airpods-4-hero-select-202409?wid=976&hei=916&fmt=jpeg&qlt=90&.v=NFNYUnZEZG9WdmVKZzdXRW9IVzNoQVV5N29UUE5sYkU5bzFjbnV4MlZFL2kyVU55U21PWTMyajVGNTlWWnhwak14MXJScFRZN3Y5OWZsRXVrN1k4cFZyQ2FPOWYvcVVkNFcyRXFtUGhFUW8" alt="AirPods 4" class="product-image">
            <p>Opis: Doživite naslednjo raven zvoka z AirPods 4. Z izboljšano kakovostjo zvoka in brezskrbno povezljivostjo.</p>
            <p class="price">Cena: €89.99</p>
        </div>
        <div class="product">
            <h3>Armani Acqua di Gio</h3>
            <img src="https://assets.armani.com/image/upload/f_auto,q_auto:best,ar_4:5,w_1350,c_fill/LE311500_NLP_100ML_F_FW2025.jpg" alt="Armani Acqua di Gio" class="product-image">
            <p>Opis: Armani Acqua di Gio je osvežujoča dišava, ki uteleša bistvo morja. Popolna za vsako priložnost.</p>
            <p class="price">Cena: €92.99</p>
        </div>
        <!-- Dodajte še 3 slike in opise po potrebi -->
    </div>
</body>
</html>
