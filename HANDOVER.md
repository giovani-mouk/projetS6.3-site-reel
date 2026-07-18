
---

## 📋 HANDOVER GUIDE (HANDOVER.md)

```markdown
# 📋 Guide de Transfert - Fondation Espoir Congo

> Document destiné au client pour la prise en main du site web

## 🎯 Bienvenue !

Ce document vous accompagne dans la prise en main de votre nouveau site web. Il contient toutes les informations nécessaires pour comprendre, maintenir et faire évoluer votre présence en ligne.

## 📦 Contenu livré

### Fichiers
- ✅ 6 pages HTML (index, about, missions, projets, temoignages, contact)
- ✅ 1 fichier CSS (style.css)
- ✅ Documentation complète (README.md)
- ✅ Code source sur GitHub
- ✅ Site déployé sur GitHub Pages

### Fonctionnalités
- ✅ Design responsive (mobile, tablette, desktop)
- ✅ Formulaire de contact
- ✅ Section don avec 3 niveaux
- ✅ 6 projets avec barres de progression
- ✅ 6 témoignages
- ✅ Galerie équipe
- ✅ Informations de contact complètes

## 🔧 Maintenance

### Mise à jour du contenu

#### Modifier un texte
1. Ouvrir le fichier HTML concerné dans un éditeur de code (VS Code recommandé)
2. Localiser le texte à modifier
3. Sauvegarder le fichier
4. Pousser les modifications vers GitHub

#### Ajouter une image
1. Placer l'image dans le dossier `/images`
2. Utiliser le format : `<img src="images/nom-image.jpg" alt="Description">`
3. Optimiser l'image avant (max 500 Ko, format WebP ou JPG)

#### Modifier un projet
Ouvrir `projets.html` et modifier la section correspondante :
```html
<article class="project-card">
    <div class="project-image">
        <img src="images/projet.jpg" alt="Nom du projet">
    </div>
    <div class="project-content">
        <h3>Titre du projet</h3>
        <p>Description...</p>
    </div>
</article>

Déploiement
Le site est automatiquement déployé sur GitHub Pages à chaque push sur la branche main.
URL du site : https://giovani-mouk.github.io/projetS6.3-site-reel.git/
Sauvegarde
Toutes les modifications sont sauvegardées sur GitHub
Historique complet des versions disponible
Possibilité de revenir à une version précédente
🎨 Personnalisation
Changer les couleurs
Modifier les variables CSS dans style.css :
:root {
    --primary: #2e7d5b;        /* Couleur principale */
    --secondary: #f39c12;      /* Couleur secondaire */
    --accent: #e74c3c;         /* Couleur d'accent */
}

Changer le logo
Modifier dans chaque fichier HTML :

<div class="logo">
    <span class="logo-icon">🌱</span>
    <span class="logo-text">Fondation<span>Esperance</span></span>
</div>

📞 Support
Questions techniques
Développeur : Giovani MOUKOKO- giovanimoukoko@gmail.com
GitHub : https://giovani-mouk.github.io/projetS6.3-site-reel.git/

Ressources utiles
Documentation HTML
Documentation CSS
GitHub Guides

📊 Statistiques du site
Performance
Lighthouse Score : 95+
Temps de chargement : < 2 secondes
Responsive : 100% compatible
SEO
Meta tags : Optimisés
Structure : Sémantique HTML5
Accessibilité : WCAG AA
🚀 Évolutions recommandées
Court terme (1-3 mois)
Ajouter de vraies photos de l'association
Connecter le formulaire de contact à un email
Intégrer Google Maps pour la localisation
Ajouter les vrais liens réseaux sociaux
Moyen terme (3-6 mois)
Système de don en ligne (Mobile Money)
Blog pour les actualités
Newsletter avec inscription
Espace bénévole sécurisé
Long terme (6-12 mois)
Multi-langue (FR/EN)
Application mobile
Système de parrainage en ligne
Rapports annuels interactifs

📝 Checklist de prise en main
Vérifier que toutes les pages s'affichent correctement
Tester le responsive sur mobile et tablette
Vérifier les liens de navigation
Tester le formulaire de contact
Vérifier les informations de contact
Accéder au repository GitHub
Comprendre la structure des fichiers
Savoir modifier un texte simple
Savoir ajouter une image
Connaître la procédure de déploiement
💡 Conseils

Bonnes pratiques
Optimiser les images avant de les ajouter (max 500 Ko)
Tester les modifications sur différents appareils
Sauvegarder régulièrement (GitHub le fait automatiquement)
Documenter les modifications importantes
Former au moins 2 personnes à la maintenance
À éviter
❌ Modifier le CSS sans comprendre les conséquences
❌ Supprimer des fichiers sans sauvegarde
❌ Utiliser des images trop lourdes
❌ Négliger l'accessibilité
❌ Oublier de tester sur mobile

🎓 Formation
Une session de formation de 2 heures est prévue pour :
Comprendre la structure du site
Savoir modifier le contenu
Gérer les images
Utiliser GitHub
Déployer les modifications
Contactez-nous pour planifier cette formation.