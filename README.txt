BOUNCER — VERSION PWA

Fichiers :
- index.html : le jeu + bouton d'installation
- manifest.json : identité de l'application
- sw.js : cache/offline
- icon*.svg : icônes

IMPORTANT :
Pour que l'installation PWA fonctionne, le site doit être publié sur une adresse HTTPS
(ex. votre-domaine.com). Ouvrir index.html directement avec file:// ne permet pas
l'enregistrement du Service Worker.

Android/Chrome : le bouton « INSTALLER L'APPLICATION » apparaît quand le navigateur
autorise l'installation.

iPhone/iPad : Safari utilise « Partager » → « Sur l’écran d’accueil ».
