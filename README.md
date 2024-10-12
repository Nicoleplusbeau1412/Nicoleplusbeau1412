<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Apiculture du Nord</title>
</head>
<body>
    <header>
        <h1>Apiculture du Nord</h1>
        <nav>
            <ul>
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#produits">Produits</a></li>
                <li><a href="#apropos">À propos</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="accueil">
        <h2>Bienvenue dans notre monde de miel</h2>
        <p>Nous produisons du miel, des bougies et de l'hydromel, issus de la belle région du Nord de la France.</p>
    </section>
    
    <section id="produits">
        <h2>Nos Produits</h2>
        <div class="produit">
            <h3>Miel</h3>
            <p>Miel pur et naturel, récolté avec soin.</p>
            <img src="miel.jpg" alt="Miel">
        </div>
        <div class="produit">
            <h3>Bougies</h3>
            <p>Bougies en cire d'abeille, pour une ambiance chaleureuse.</p>
            <img src="bougies.jpg" alt="Bougies">
        </div>
        <div class="produit">
            <h3>Hydromel</h3>
            <p>Hydromel artisanal, pour des moments festifs.</p>
            <img src="hydromel.jpg" alt="Hydromel">
        </div>
    </section>
    
    <section id="apropos">
        <h2>À propos</h2>
        <p>Notre entreprise d'apiculture s'engage à produire des produits locaux et durables. Découvrez notre histoire et notre passion pour les abeilles.</p>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <form>
            <label for="nom">Nom :</label>
            <input type="text" id="nom" name="nom" required>
            
            <label for="email">Email :</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message :</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Envoyer</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2024 Apiculture du Nord</p>
    </footer>
</body>
</html>
