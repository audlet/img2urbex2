# img2urbex2<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UrbexiF - Explorez l'urbex</title>
    <style>
        /* Style général */
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            color: #333;
            background-color: #f8f8f8;
            text-align: center;
        }

        /* En-tête */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
            background-color: #1f1f1f;
            color: white;
        }

        header .logo {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        header .logo img {
            height: 30px;
        }

        header .menu {
            font-size: 24px;
            cursor: pointer;
        }

        /* Section principale */
        .main-section {
            background-color: white;
            margin: 20px;
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .main-section h1 {
            font-size: 2em;
            color: #1f1f1f;
        }

        .main-section p {
            font-size: 1em;
            color: #666;
            margin-top: 10px;
            line-height: 1.5;
        }

        /* Statistiques */
        .stats {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }

        .stat {
            text-align: center;
        }

        .stat h2 {
            font-size: 2em;
            color: #1f1f1f;
        }

        .stat p {
            font-size: 1em;
            color: #666;
        }

        /* Boutons */
        .actions {
            margin-top: 20px;
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        .actions a {
            text-decoration: none;
            padding: 10px 20px;
            border: 2px solid #1f1f1f;
            border-radius: 5px;
            color: #1f1f1f;
            font-size: 1em;
            transition: all 0.3s ease;
        }

        .actions a:hover {
            background-color: #1f1f1f;
            color: white;
        }
    </style>
</head>
<body>
    <!-- En-tête -->
    <header>
        <div class="logo">
            <img src="https://via.placeholder.com/100x30?text=URBEXIF" alt="Logo UrbexiF">
        </div>
        <div class="menu">☰</div>
    </header>

    <!-- Section principale -->
    <div class="main-section">
        <h1>Explorez l'urbex avec nous</h1>
        <p>Bienvenue sur UrbexiF, votre plateforme communautaire dédiée à l'exploration urbaine, alliant adrénaline, sécurité et créativité à travers des expériences uniques et un objet connecté innovant.</p>

        <!-- Statistiques -->
        <div class="stats">
            <div class="stat">
                <h2>150+</h2>
                <p>Aventures partagées</p>
            </div>
            <div class="stat">
                <h2>15</h2>
                <p>Communauté engagée</p>
            </div>
        </div>

        <!-- Boutons d'action -->
        <div class="actions">
            <a href="#">Commencer</a>
            <a href="#">Découvrir</a>
        </div>
    </div>
</body>
</html>
