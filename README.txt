MA ROUE DE LA FORTUNE — version Android

Contenu :
- index.html : application
- manifest.json : informations d'installation
- service-worker.js : cache hors ligne
- icon-192.png / icon-512.png : icônes

IMPORTANT :
Pour que Chrome sur Android propose « Installer l'application » ou « Ajouter à l'écran d'accueil » avec le mode application et le fonctionnement hors ligne, ces fichiers doivent être publiés sur une adresse HTTPS. Ouvrir index.html depuis un fichier local ne suffit généralement pas pour installer une PWA.

Méthode gratuite possible :
1. Publier ces fichiers sur un hébergement statique HTTPS gratuit (par exemple GitHub Pages).
2. Ouvrir l'adresse HTTPS dans Chrome sur la Samsung Tab.
3. Menu ⋮ > Installer l'application ou Ajouter à l'écran d'accueil.
4. Ouvrir l'icône « Ma roue ».

Les roues sont enregistrées localement dans Chrome sur la tablette. Utiliser régulièrement « Exporter mes roues » pour créer une sauvegarde JSON, car la suppression des données du navigateur peut effacer les roues locales.
