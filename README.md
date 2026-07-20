# Mes contributions au projet Alaska

Alaska est une boutique en ligne de manteaux d'hiver techniques, développée sous WordPress avec WooCommerce dans le cadre d'un stage chez Pandora Brand Marketing. Ce dépôt ne contient pas le code du projet (privé), uniquement la description de mes contributions. Le projet a été réalisé en équipe ; voici les détails de mes contributions.

## Pages développées

- **Accueil** : conversion de la maquette en gabarit WordPress, sections dynamiques (hero, mises en avant, Instagram, meilleures ventes).
- **À propos** : page héritage/histoire de la marque, avec médias et textes gérables via ACF.
- **Technologies** : présentation des technologies produit, avec schéma illustratif et sections animées.
- **Journal** : aperçu des articles récents (3 derniers), avec photos de repli cohérentes.
- **Lookbook** : galerie de campagne, bloc mosaïque texte/photos, adapté pour mobile.
- **Articles** : archive complète et paginée du blog, avec filtres par catégorie, date et langue.
- **Campagnes** : page de détail d'une campagne/collection, avec image de repli et contenu dynamique.

Pour chacune de ces pages : intégration du gabarit PHP à partir de la maquette, création des groupes de champs ACF Pro (photos et textes), mise en place d'images de repli, et adaptation du contenu au support bilingue FR/EN.

## Fonctionnalités transversales

- **Design responsive** du site sur plusieurs points de rupture (mobile, tablette, desktop).
- **Page Boutique personnalisée** avec filtres par catégorie (Homme/Femme/Enfant).
- **Fonctions utilitaires multilingues** pour la résolution automatique des URLs traduites (Polylang).
- **Logique de filtrage et d'affichage de contenu** adaptée à la langue active (catégories, articles, menus).
- **Intégration SMTP native** pour l'envoi de courriels, sans plugin tiers.
- **Formulaire d'infolettre** avec validation et messages de statut.
- **Résolution d'un bug WordPress core** lié à l'API REST (échec de sauvegarde d'une page causé par un champ meta spécifique).

## Workflow

- Développement sur une branche personnelle (`cad`), synchronisée avec `test` avant intégration.
- Résolution des conflits de fusion (merge) lors de l'intégration du travail d'équipe.
- Commits suivant la convention *Conventional Commits* (`feat`, `fix`, etc.).

## Stack technique

WordPress · PHP 8 · WooCommerce · ACF Pro · Polylang · CSS3 · JavaScript · Git/GitHub
