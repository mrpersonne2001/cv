<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon CV</title>
    <style>
        /* Styles généraux */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            background-color: #f4f4f4;
            color: #333;
        }

        .container {
            max-width: 900px;
            margin: auto;
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h1, h2 {
            color: #0056b3;
            border-bottom: 2px solid #0056b3;
            padding-bottom: 5px;
            margin-top: 20px;
        }

        h1 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 30px;
        }

        /* Section Informations personnelles */
        .personal-info p {
            margin: 5px 0;
        }

        .personal-info strong {
            color: #0056b3;
        }

        /* Sections Expérience et Formation */
        .section-item {
            margin-bottom: 20px;
        }

        .section-item h3 {
            margin-top: 0;
            color: #333;
        }

        .section-item p {
            margin: 5px 0;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            background: #e9e9e9;
            margin-bottom: 5px;
            padding: 8px 15px;
            border-left: 5px solid #007bff;
        }

        /* Compétences */
        .skills ul {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .skills ul li {
            background: #007bff;
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            border-left: none; /* Override default list style */
        }

        /* Intérêts */
        .interests ul {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .interests ul li {
            background: #6c757d;
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            border-left: none; /* Override default list style */
        }

        /* Pied de page (optionnel) */
        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 0.9em;
            color: #666;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Votre Nom et Prénom</h1>
            <p style="text-align: center;">Votre Titre Professionnel (Ex: Développeur Web, Chef de Projet)</p>
        </header>

        <hr>

        <section class="personal-info">
            <h2>Informations Personnelles</h2>
            <p><strong>Adresse :</strong> Votre Rue, Votre Ville, Code Postal</p>
            <p><strong>Téléphone :</strong> ‪+33 1 23 45 67 89‬</p>
            <p><strong>Email :</strong> votre.email@example.com</p>
            <p><strong>LinkedIn :</strong> <a href="https://www.linkedin.com/in/votrenom" target="_blank">linkedin.com/in/votrenom</a></p>
            <p><strong>Portfolio/GitHub :</strong> <a href="https://www.votresite.com" target="_blank">votresite.com</a></p>
        </section>

        <hr>

        <section class="summary">
            <h2>À Propos de Moi</h2>
            <p>
                Rédigez ici un court paragraphe qui présente votre parcours, vos compétences clés et vos objectifs de carrière.
                C'est une section importante pour capter l'attention du recruteur. Soyez concis et percutant.
                Par exemple : "Développeur web passionné avec X années d'expérience en [technologie 1] et [technologie 2].
                Recherche un poste stimulant où je pourrai mettre à profit mes compétences en [domaine] et contribuer au succès de l'entreprise."
            </p>
        </section>

        <hr>

        <section class="experience">
            <h2>Expérience Professionnelle</h2>
            <div class="section-item">
                <h3>Poste Occupé | Nom de l'Entreprise</h3>
                <p><strong>Durée :</strong> Mois Année - Mois Année (ou "Présent") | Ville, Pays</p>
                <ul>
                    <li>Description de vos responsabilités et réalisations clés. Utilisez des verbes d'action.</li>
                    <li>Quantifiez vos succès lorsque c'est possible (ex: "Augmentation de X% des ventes").</li>
                    <li>Mettez en avant les compétences utilisées.</li>
                </ul>
            </div>
            <div class="section-item">
                <h3>Autre Poste | Autre Entreprise</h3>
                <p><strong>Durée :</strong> Mois Année - Mois Année | Ville, Pays</p>
                <ul>
                    <li>Description des responsabilités et réalisations.</li>
                    <li>Utilisez des puces pour une meilleure lisibilité.</li>
                </ul>
            </div>
            </section>

        <hr>

        <section class="education">
            <h2>Formation</h2>
            <div class="section-item">
                <h3>Diplôme/Titre | Nom de l'Établissement</h3>
                <p><strong>Années :</strong> Année de début - Année de fin | Ville, Pays</p>
                <ul>
                    <li>Mention obtenue (si applicable)</li>
                    <li>Projets pertinents ou cours clés</li>
                </ul>
            </div>
            <div class="section-item">
                <h3>Autre Diplôme | Autre Établissement</h3>
                <p><strong>Années :</strong> Année de début - Année de fin | Ville, Pays</p>
            </div>
            </section>

        <hr>

        <section class="skills">
            <h2>Compétences</h2>
            <ul>
                <li>HTML5</li>
                <li>CSS3</li>
                <li>JavaScript</li>
                <li>Python</li>
                <li>React</li>
                <li>Node.js</li>
                <li>Gestion de Projet</li>
                <li>Communication</li>
                <li>Travail d'équipe</li>
            </ul>
        </section>

        <hr>

        <section class="languages">
            <h2>Langues</h2>
            <ul>
                <li>Français : Langue maternelle</li>
                <li>Anglais : Courant (C1)</li>
                <li>Espagnol : Intermédiaire (B2)</li>
            </ul>
        </section>

        <hr>

        <section class="interests">
            <h2>Centres d'Intérêt</h2>
            <ul>
                <li>Lecture</li>
                <li>Voyages</li>
                <li>Photographie</li>
                <li>Sport (randonnée, natation)</li>
            </ul>
        </section>

        <footer>
            <p>&copy; 2025 Votre Nom. Tous droits réservés.</p>
        </footer>
    </div>
</body>
</html>
