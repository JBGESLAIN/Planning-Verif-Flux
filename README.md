# 📅 Planning Vérification Flux

Application web moderne pour gérer la rotation de vérification des flux au sein d'une équipe.

## 🎯 Objectif Principal

Afficher **qui est responsable de la vérification des Flux cette semaine** de manière claire, visuelle et agréable.

## 👥 Équipe

- **JB** 🟢 (#92d050)
- **Damien** 🟠 (#f4b183)
- **Loic** 🔵 (#5b9bd5)

## 📋 Fonctionnalités

### Carte Principale
- Numéro de semaine ISO
- Nom du responsable en couleur
- Dates de la semaine
- Animations et design responsive

### Gestion des Vacances
- Ajout/suppression de périodes de vacances
- Sauvegarde automatique en LocalStorage
- Rotation intelligente en cas d'absence
- Équité préservée à long terme

### Tableau Détails
- Affichage de 52 semaines
- Calcul automatique du responsable
- Prise en compte des vacances
- Design moderne et responsive

## 🔧 Caractéristiques Techniques

- **Un seul composant** fonctionnel et complet
- **Code propre et commenté** - Aucun doublon
- **Gestion correcte des dates** - Calcul ISO des semaines
- **Calcul automatique** - Rotation nominale JB → Damien → Loic
- **Responsive** - Optimisé pour mobile, tablette et desktop
- **Pas de dépendances** - HTML/CSS/JavaScript pur

## 📱 Utilisation

1. Consulter le responsable de la semaine en cours
2. Ajouter les périodes de vacances
3. Visualiser le planning sur 52 semaines
4. Les congés sont automatiquement sauvegardés

## 🚀 Déploiement

L'application est automatiquement déployée sur GitHub Pages à chaque push sur `develop` ou `main`.

Accédez à : `https://JBGESLAIN.github.io/Planning-Verif-Flux`

## 📐 Règles Métier

### Rotation Nominale
```
JB → Damien → Loic → JB → Damien → Loic ...
```

### Semaines de Départ
- 29/06/2026 - 05/07/2026 : **JB**
- 06/07/2026 - 12/07/2026 : **Damien**
- 13/07/2026 - 19/07/2026 : **Loic**

### Gestion des Vacances
✅ Si un collaborateur est absent lors de son tour :
- Son tour est reporté
- Il ne perd jamais son tour
- Le premier disponible prend temporairement la semaine
- L'équité est préservée sur le long terme

## 📦 Structure

```
Planning-Verif-Flux/
├── index.html          # Application complète (HTML + CSS + JS)
├── .github/workflows/
│   └── deploy.yml      # Workflow de déploiement GitHub Pages
└── README.md           # Documentation
```

## 🎨 Design

- Dégradé violet moderne
- Cartes avec ombres et coins arrondis
- Animations fluides
- Responsive sur tous les appareils
- Codes couleur pour chaque collaborateur

## 💾 Persistance

Les congés sont sauvegardés en LocalStorage et persistent entre les sessions.

---

**Créé avec ❤️ pour une meilleure gestion d'équipe**
