# MOTION TEXT PRO — Android starter

Première base native Android en Kotlin + Jetpack Compose.

## Ouvrir le projet
1. Décompresser `MotionTextPro-Android.zip`.
2. Ouvrir le dossier `MotionTextPro` dans Android Studio.
3. Laisser Gradle effectuer la synchronisation.
4. Lancer sur un téléphone Android ou un émulateur.

## Générer un APK
Dans Android Studio : **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
L'APK debug est généralement créé dans `app/build/outputs/apk/debug/`.

## État de cette version
- Interface Android native.
- Import de fichier audio via le sélecteur Android.
- Édition du texte.
- Aperçu animé avec effets Zoom, Fondu et Pulse.
- Base de projet prête pour les prochaines étapes.

## À développer ensuite
- Transcription réelle d'un fichier audio importé (service Speech-to-Text).
- Découpage et synchronisation des mots avec les horodatages.
- Timeline avec réglages individuels par séquence.
- Bibliothèque de modèles 2D/3D.
- Rendu et export MP4.

Important : l'import audio est présent, mais cette version ne transcrit pas encore le fichier et ne génère pas encore de vidéo MP4.
