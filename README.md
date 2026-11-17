# Carte de visite — application Android (Jetpack Compose)

Exercice d'apprentissage du développement Android : une application d'un écran qui affiche une carte de visite, construite avec Jetpack Compose.

## Ce que fait l'application

Un écran centré présente :

- un logo / image de profil ;
- un nom et un titre (le titre est encore un texte d'exemple, « Votre Titre ») ;
- un numéro de téléphone et une adresse e-mail ;
- deux icônes (Gmail et téléphone).

## Notions travaillées

- Fonctions `@Composable` et aperçu avec `@Preview`
- Mise en page avec `Column`, `Row`, `Spacer` et `Modifier`
- Affichage d'images depuis les ressources (`painterResource`)
- Typographie Material 3 et thème personnalisé
- Structure d'un projet Android avec Gradle (Kotlin DSL, catalogue de versions)

## Stack

- Kotlin 1.9, Jetpack Compose (BOM 2024.04.01), Material 3
- Android Gradle Plugin 8.6, `compileSdk` 34, `minSdk` 24

## Lancer le projet

1. Ouvrir le dossier du dépôt dans **Android Studio**.
2. Laisser Gradle synchroniser le projet.
3. Lancer l'application (bouton **Run**) sur un émulateur ou un appareil Android 7.0+ (API 24).

En ligne de commande, `./gradlew assembleDebug` (ou `gradlew.bat assembleDebug` sous Windows) génère l'APK de debug.
