# S.O.S électrique — projet Android

Ce projet encapsule l'application HTML dans une application Android WebView.

## Générer l'APK
1. Crée un dépôt GitHub vide nommé `SOS-Electrique`.
2. Envoie tous les fichiers de ce dossier dans le dépôt (y compris `.github/workflows`).
3. Ouvre l'onglet **Actions** du dépôt.
4. Lance **Build S.O.S électrique APK** avec **Run workflow** (ou attends la compilation après le push).
5. Quand le travail est terminé, ouvre le résultat **SOS-electrique-debug-apk** dans **Artifacts** et télécharge-le.
6. Décompresse l'archive téléchargée : tu trouveras `app-debug.apk`. Ouvre-le sur ton Android pour l'installer.

La compilation doit être exécutée par GitHub Actions, car l'environnement de préparation ici ne contient pas Android SDK/Gradle.
C'est un APK de test (debug), non signé pour publication Play Store.
