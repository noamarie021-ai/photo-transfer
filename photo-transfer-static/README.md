# Photo Transfer — iPhone (page web) ↔ Android (app native)

## Côté iPhone : toujours la page web
Même déploiement qu'avant (gratuit, une seule fois) :
- Dépose le contenu de ce dossier sur Cloudflare Pages ou GitHub Pages (HTTPS obligatoire pour la caméra).
- Sur l'iPhone, Safari > Partager > Sur l'écran d'accueil.

## Appairage (même Wi-Fi)
1. iPhone : « Envoyer (depuis l'iPhone) » → QR code affiché.
2. Android : ouvre l'app Photo Transfer (voir l'autre dossier/zip) → « Se connecter à l'iPhone » → scanne ce QR code → un second QR code s'affiche sur l'Android.
3. iPhone : « Scanner le code de l'Android » → scanne-le. La connexion s'établit.

## Une fois connecté
- iPhone → Android : choisis des photos sur l'iPhone, touche Envoyer. Elles arrivent sur l'Android, dans l'ordre, qualité d'origine.
- Android → iPhone (automatique) : sur l'Android, touche « Envoyer les nouveaux fichiers ». Tous les fichiers nouveaux depuis le dernier envoi (galerie + autres dossiers, si la permission « Tous les fichiers » a été accordée) arrivent sur l'écran d'envoi de l'iPhone, avec un bouton pour les enregistrer.

Les deux sens utilisent la même connexion, sans rescanner de code entre les deux.
