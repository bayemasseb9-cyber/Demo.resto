# Demo.resto
C'est une démonstration de site
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saveurs du Sénégal | Menu Digital</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com">
    <style>
        :root { --gold: #c5a059; --dark: #1a1a1a; --white: #ffffff; }
        body { font-family: 'Playfair Display', serif; margin: 0; background: #fdfdfd; }
        
        /* Hero Section */
        .hero { 
            height: 60vh; 
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
                        url('https://images.unsplash.com');
            background-size: cover; background-position: center;
            display: flex; flex-direction: column; justify-content: center; align-items: center;
            color: white; text-align: center;
        }

        /* Menu Grid */
        .menu-container { max-width: 1000px; margin: -50px auto 50px; padding: 20px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 25px; }
        
        .food-card { 
            background: white; border-radius: 15px; overflow: hidden; 
            box-shadow: 0 10px 20px rgba(0,0,0,0.05); transition: 0.3s;
        }
        .food-card:hover { transform: translateY(-5px); }
        .food-img { width: 100%; height: 200px; object-fit: cover; }
        
        .food-info { padding: 20px; text-align: center; }
        .price { color: var(--gold); font-weight: bold; font-size: 1.2rem; display: block; margin: 10px 0; }
        
        /* Bouton WhatsApp stylé */
        .btn-order { 
            background: #25d366; color: white; text-decoration: none; 
            padding: 10px 20px; border-radius: 50px; display: inline-flex; 
            align-items: center; gap: 8px; font-weight: bold; font-size: 0.9rem;
        }
    </style>
</head>
<body>

<section class="hero">
    <h1>Saveurs du Sénégal</h1>
    <p>Le goût de l'authenticité livré chez vous</p>
</section>

<div class="menu-container">
    <div class="grid">
        <!-- Plat 1 -->
        <div class="food-card">
            <img src="image 0.jpg" class="food-img">
            <div class="food-info">
                <h3>Thieboudienne Royal</h3>
                <p>Le plat national préparé avec amour.</p>
                <span class="price">3 500 FCFA</span>
                <a href="https://wa.me" class="btn-order">
                    <i class="fab fa-whatsapp"></i> Commander
                </a>
            </div>
        </div>

<!-- Plat 2 -->
        <div class="food-card">
            <img src="image 3.jpg" class="food-img">
            <div class="food-info">
                <h3>Mafé</h3>
                <p>Le plat préparé a base d'arrachide.</p>
                <span class="price">4 500 FCFA</span>
                <a href="https://wa.me" class="btn-order">
                    <i class="fab fa-whatsapp"></i> Commander
                </a>
            </div>
        </div>
        
        <!-- Plat 3 -->
        <div class="food-card">
            <img src="image 1.jpg" class="food-img">
            <div class="food-info">
                <h3>Thieboudienne simple</h3>
                <p>Le plat preparé avec du riz ,poisson et sauz.</p>
                <span class="price">1 500 FCFA</span>
                <a href="https://wa.me" class="btn-order">
                    <i class="fab fa-whatsapp"></i> Commander
                </a>
            </div>
        </div>

        <!-- Plat 4 -->
        <div class="food-card">
            <img src="image 2.jpg" class="food-img">
            <div class="food-info">
                <h3>Yassa Poulet</h3>
                <p>Oignons caramélisés et poulet braisé.</p>
                <span class="price">2 500 FCFA</span>
                <a href="https://wa.me" class="btn-order">
                    <i class="fab fa-whatsapp"></i> Commander
                </a>
            </div>
        </div>
    </div>
   </div>    

</body>
</html>
