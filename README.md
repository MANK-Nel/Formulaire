# Formulaire CV Chronos

Ce projet est un formulaire web moderne permettant la création et la transmission de CV professionnels, avec structuration dynamique des données, envoi par email (Formspree), et navigation optimisée pour mobile et desktop.

## Fonctionnalités principales
- Onboarding et sélection de profil
- Formulaire dynamique pour expériences, formations, compétences
- Structuration HTML des données pour email
- Bouton de retour à l'accueil
- Responsive design (mobile/desktop)
- Téléchargement catalogue PDF
- Guide d'aide interactif
- Hébergement compatible Vercel

## Installation et lancement local

1. **Cloner le dépôt**
   ```sh
   git clone https://github.com/MANK-Nel/Formulaire.git
   cd Formulaire
   ```
2. **Installer les dépendances**
   ```sh
   npm install
   ```
3. **Lancer le serveur de développement**
   ```sh
   npm run dev
   ```

## Déploiement sur Vercel

1. Connectez votre dépôt GitHub à Vercel
2. Vercel détecte automatiquement le projet (Vite/React)
3. Configurez le build command :
   ```sh
   npm run build
   ```
   et le dossier de sortie :
   ```sh
   dist
   ```
4. Déployez !

## Configuration Vercel
- **Framework** : Vite (React)
- **Build Command** : `npm run build`
- **Output Directory** : `dist`
- **Node.js version** : 18+ recommandée

## Conseils
- Vérifiez que le fichier `formulaire-original.html` est bien dans le dossier public ou dist pour l'accès direct.
- Les images et assets doivent être dans le dossier public ou référencés correctement.
- Les formulaires utilisent Formspree, aucune configuration backend nécessaire.

## Auteur
MANK-Nel

---
Pour toute question ou bug, ouvrez une issue sur GitHub.
