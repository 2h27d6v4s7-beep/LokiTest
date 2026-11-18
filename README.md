# LokiTest — prototype iPhone

## Tester immédiatement
Ouvre `index.html` dans un navigateur pour prévisualiser l'interface. La connexion est une démonstration locale : n'utilise pas un vrai mot de passe.

## Installation comme application sur iPhone (sans Mac)
Une PWA doit être publiée sur une adresse HTTPS pour que Safari puisse l'ajouter à l'écran d'accueil et activer le mode hors ligne.

1. Crée un compte GitHub si tu n'en as pas.
2. Dans Safari, ouvre github.com et crée un nouveau dépôt public nommé `lokitest`.
3. Ajoute les fichiers de ce dossier à la racine du dépôt (`index.html`, `manifest.webmanifest`, `sw.js`, dossier `icons`).
4. Dans le dépôt, ouvre Settings → Pages.
5. Dans Build and deployment, choisis Deploy from a branch, branche `main`, dossier `/ (root)`, puis Save.
6. Attends la publication. L'adresse sera de la forme `https://TON-PSEUDO.github.io/lokitest/`.
7. Ouvre cette adresse dans Safari sur ton iPhone → bouton Partager → Sur l'écran d'accueil → Ajouter.

## Limites de cette version
- Connexion et profil stockés localement dans le navigateur, sans authentification serveur.
- Chat simulé, sans échange entre plusieurs utilisateurs.
- Notifications affichées dans l'app ; pas de notifications push.
- Ne saisis aucun mot de passe réel ni donnée sensible.
- Pour une vraie application multi-utilisateur, il faudra ajouter un backend sécurisé, une authentification et une configuration de notifications.
