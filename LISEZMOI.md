# Inventaire Caméra — application Android

Application Android (APK) qui fait l'inventaire des coffrets par caméra et IA Claude.
L'écran reste allumé pendant l'utilisation ; l'export Excel s'envoie par WhatsApp, e-mail, Drive…

## Obtenir l'APK sans rien installer (GitHub, gratuit)
1. Créez un compte sur github.com puis un nouveau dépôt (New repository), par ex. `inventaire-camera`.
2. Dans le dépôt : "Add file" → "Upload files" → glissez TOUT le contenu de ce dossier
   (y compris le dossier `.github`), puis "Commit changes".
3. Onglet **Actions** : la compilation "Construire l'APK" démarre (3 à 6 minutes).
4. Quand elle est verte, ouvrez-la → en bas, "Artifacts" → **InventaireCamera-apk** → téléchargez le zip.
5. Le zip contient `InventaireCamera.apk`. Copiez-le sur le téléphone.

## Installer sur le téléphone
1. Ouvrez le fichier `InventaireCamera.apk` sur le téléphone.
2. Android demande d'autoriser l'installation d'applications inconnues → autorisez pour cette source.
3. Ouvrez "Inventaire Caméra", touchez "Démarrer la caméra", autorisez la caméra.
4. Dans Réglages, collez votre clé API Claude (console.anthropic.com).

## Avec Android Studio (alternative)
Ouvrez ce dossier dans Android Studio → Build → Build APK(s).

## Modifier l'application
Toute l'interface est dans `app/src/main/assets/index.html`.
