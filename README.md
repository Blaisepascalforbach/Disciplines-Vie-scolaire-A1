# Mon lycée A1 — application téléphone

## Publier avec GitHub Pages

1. Décompresser le ZIP.
2. Créer un dépôt GitHub et téléverser à sa racine les six fichiers de ce dossier : index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png et ce README.
3. Dans Settings → Pages, choisir Deploy from a branch, la branche main et le dossier /(root).
4. Partager l’adresse HTTPS créée par GitHub Pages. Sur le téléphone, ouvrir cette adresse puis choisir Ajouter à l’écran d’accueil ou Installer l’application.

Le contenu de l’application est mis en cache après une première ouverture. Le micro nécessite une connexion HTTPS, l’autorisation de l’élève et un navigateur compatible. L’enregistrement audio local n’est pas envoyé ni conservé par l’application.

## Voix naturelle Google

Le point d’intégration est window.OEPRE_GOOGLE_TTS({ text, languageCode, speakingRate, speaker }). Codes préparés : fr-FR, ar-001, ps-AF, ka-GE, tr-TR. L’adaptateur devra appeler un serveur qui contacte Google Cloud Text-to-Speech ; ne pas placer la clé API dans les fichiers publiés. Sans adaptateur, la voix du navigateur est utilisée lorsqu’elle est disponible.

## Repère pédagogique

L’emploi du temps affiché est un exemple. Les salles, démarches de retard ou d’absence et rôles des adultes peuvent varier selon l’établissement. L’élève est invité à vérifier les consignes auprès de la vie scolaire ou d’un adulte.
