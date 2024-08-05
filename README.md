<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Baptiste Gabez Communication</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Accueil</a></li>
                <li><a href="#about">À Propos</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#testimonials">Témoignages</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="animate__animated animate__fadeIn">
        <h1>Bienvenue sur le portfolio de Baptiste Gabez</h1>
        <p>Expert en graphisme sportif et community management.</p>
        <img src="background-image.jpg" alt="Image de fond">
    </section>

    <section id="about" class="animate__animated animate__fadeInLeft">
        <h2>À Propos</h2>
        <p>Je suis Baptiste Gabez, passionné par le sport avec une licence en management du sport et une expérience significative en tant que community manager pour des clubs professionnels de basket...</p>
        <img src="photo-professionnelle.jpg" alt="Photo professionnelle">
    </section>

    <section id="services" class="animate__animated animate__fadeInRight">
        <h2>Services</h2>
        <ul>
            <li>Création de logos : Conception de logos uniques et mémorables pour votre équipe sportive.</li>
            <li>Design de maillots : Design de maillots et équipements sportifs personnalisés.</li>
            <li>Gestion des réseaux sociaux : Augmentez votre visibilité en ligne grâce à une gestion professionnelle de vos comptes de réseaux sociaux.</li>
            <li>Montage vidéo : Montage de vidéos pour campagnes publicitaires, vidéos institutionnelles, tutoriels ou contenus pour réseaux sociaux.</li>
            <li>Conception de présentations professionnelles : Création de présentations PowerPoint personnalisées pour conférences, réunions d'entreprise, propositions commerciales, ou séminaires éducatifs.</li>
        </ul>
    </section>

    <section id="portfolio" class="animate__animated animate__fadeInUp">
        <h2>Portfolio</h2>
        <div class="portfolio-item">
            <img src="projet1.jpg" alt="Projet 1">
            <p>Logo pour l'équipe des Tigres. Objectif : Créer une identité visuelle forte et reconnaissable.</p>
        </div>
        <div class="portfolio-item">
            <img src="projet2.jpg" alt="Projet 2">
            <p>Design de maillots pour le club de basket XYZ.</p>
        </div>
        <div class="portfolio-item">
            <img src="projet3.jpg" alt="Projet 3">
            <p>Affiche pour un tournoi de basket. Objectif : Promouvoir l'événement et attirer des participants.</p>
        </div>
        <div class="portfolio-item">
            <img src="projet4.jpg" alt="Projet 4">
            <p>Montage vidéo pour une campagne publicitaire. Objectif : Augmenter la notoriété de la marque sur les réseaux sociaux.</p>
        </div>
    </section>

    <section id="testimonials" class="animate__animated animate__fadeInDown">
        <h2>Témoignages</h2>
        <blockquote>
            <p>"Baptiste a transformé notre image de marque. Nous avons vu une augmentation significative de l'engagement sur les réseaux sociaux."</p>
            <footer>- Marie Dupont, Directrice Marketing</footer>
        </blockquote>
        <blockquote>
            <p>"Le travail de Baptiste sur notre campagne publicitaire a été exceptionnel. Les vidéos qu'il a montées ont attiré beaucoup de nouveaux clients."</p>
            <footer>- Jean Martin, Responsable Communication</footer>
        </blockquote>
    </section>

    <section id="contact" class="animate__animated animate__fadeInUp">
        <h2>Contact</h2>
        <form id="contact-form">
            <label for="name">Nom:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Envoyer</button>
        </form>
        <div>
            <p>Email : <a href="mailto:baptistegabez.communication@gmail.com">baptistegabez.communication@gmail.com</a></p>
            <p>Téléphone : 06 89 36 76 12</p>
            <p>LinkedIn : <a href="https://www.linkedin.com/in/baptiste-gabez-54b0341bb">LinkedIn</a></p>
            <p>Instagram : <a href="https://www.instagram.com/baptistegabez_communication/">Instagram</a></p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Baptiste Gabez Communication. Tous droits réservés.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
