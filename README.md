# Portfolio Vue.js

Ce portfolio a été développé en **Vue.js 3** avec l'API Composition et le bundle **Vite** afin d'optimiser les performances et le temps de chargement.

## Objectif

Concevoir un portfolio interactif, bien structuré et performant, tout en facilitant la maintenance et l'ajout de nouvelles fonctionnalités.

## Choix techniques

- **Frontend :** Développé en **Vue.js 3** avec **Vite** pour des temps de compilation réduits et une architecture modulaire.
  - **PrimeVue 3** pour les composants UI afin d'assurer une cohérence visuelle et une ergonomie optimisée.
  - **Vue Router** pour la gestion des routes et de la navigation.
- **Backend :**
  - Utilisation des **fonctions serverless Vercel** pour simplifier l'hébergement et la scalabilité.
  - Stockage des données dans des fichiers **JSON** pour éviter une base de données et faciliter la modification du contenu.
- **Sécurité et envoi d'emails :**
  - **Google reCAPTCHA v3** intégré pour prévenir les envois automatiques indésirables.
  - **EmailJS** utilisé pour permettre l'envoi d'emails sans nécessité d'un backend dédié.
- **Internationalisation :**
  - **Vue I18n** implémenté pour assurer la traduction complète du site et une meilleure accessibilité.
- **Hébergement :**
  - Hébergement sur **Vercel** pour un déploiement automatique et une gestion simplifiée.
  - Domaine personnalisé géré via **OVH** (leochristophe.fr).

## Pages et fonctionnalités

- **Accueil :** Présentation succincte des passe temps et accès au CV en téléchargement.
- **Parcours :** Détail des expériences professionnelles et formations avec une mise en page chronologique.
- **Projets :** Présentation des réalisations avec images et descriptions techniques.
- **Compétences :** Liste des technologies et outils utilisés, illustrée par des indicateurs de maîtrise.
- **Contact :**
  - Formulaire de contact sécurisé avec **reCAPTCHA v3** et **EmailJS**.

## Optimisations et améliorations prévues

- Meilleurs adaptation mobile avec un renforcement de l'expérience utilisateur sur petits écrans.
- Ajout de tests unitaires pour mieux prévoir le comportement après changements

## Installation et lancement

```bash
# Installer les dépendances
yarn install # ou npm install

# Lancer le projet en mode développement
yarn dev # ou npm run dev

# Générer le build pour la production
yarn build # ou npm run build
```

