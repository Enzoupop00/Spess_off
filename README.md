<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site de Enzo et Maël</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Menu déroulant -->
    <div id="menu">
        <div class="menu-icon" onclick="toggleMenu()">☰</div>
        <div id="dropdownMenu" class="dropdown-content">
            <button class="dropdown-button" onclick="showPage('home')">Accueil</button>
            <button class="dropdown-button" onclick="showPage('maps')">Map Récentes</button>
            <button class="dropdown-button" onclick="showPage('players')">Players</button>
            <button class="dropdown-button" onclick="showPage('contact')">Contact</button>
        </div>
    </div>

    <!-- Contenu principal -->
    <div id="main-content">
        <!-- Section Accueil -->
        <div id="home">
            <h1>Bienvenue dans le site de Enzo et Maël</h1>
            <p>Bienvenue mon cher, tu es dans le site officiel de Enzo et Maël. Visite-le et lis bien ce qui est marqué.<br>
            <u>Cordialement Enzo</u></p>
        </div>

        <!-- Section Map Récentes -->
        <div id="maps">
            <h2>Map Récentes</h2>
            <div class="maps-container">
                <div class="map">
                    <img src="https://cdn.discordapp.com/attachments/1250512697553059925/1278010264750395552/Picsart_24-08-27_17-13-34-041.jpg?ex=66cfe80f&is=66ce968f&hm=c0abe66821fa65780be0753c7721d41b91c2dba1054d6b746438fe3254c0bb8d&" alt="Image de map">
                    <p>call of duty<br><span class="yellow-bg">Code Map: Coming Soon</span></p>
                    <button class="dropdown-button" onclick="window.open('details.html', '_blank')">Voir Détail</button>
                </div>
            </div>
        </div>

        <!-- Section Players -->
        <div id="players">
            <h2>Players</h2>
            <p>MAËL: Mael est très fort en système Fortnite. Ajouter le <a href="votre_lien_ici" target="_blank">clique ici</a></p>
        </div>

        <!-- Section Contact -->
        <div id="contact">
            <h2>Contact</h2>
            <p>Ajouter darksoo_enzoupop sur Discord</p>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <p><a href="mailto:enzoupopPro@gmail.com">Contact</a></p>
        <p>&copy; 2024 Enzo et Maël. Tous droits réservés.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
