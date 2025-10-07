---
title: "SCRUM Sprint - Landing Page"
output:
  pdf_document:
    toc: true
    toc_depth: 2
    highlight: tango
export_on_save:
  markdown: true
---

## SCRUM Landing Page

> Ce Sprint Backlog correspond à un **Sprint 1 de 1 semaine (5 jours)**, avec une équipe de développement de **3 personnes** (développeur front-end, développeur back-end, et un designer/tester — ou rôles combinés dans un contexte pédagogique).

---

## 🏃‍♂️ Sprint Backlog - Sprint 1  

**Objectif du Sprint** : Livrer un MVP fonctionnel de la landing page "Produit Alpha", responsive et permettant de collecter les e-mails des visiteurs.

**Durée** : 5 jours (du lundi au vendredi)  
**Capacité de l'équipe** : 24 heures de travail effectif (≈ 8h/jour × 3 personnes × 60 % de capacité utile = ~24h)

---

### ✅ Éléments sélectionnés du Product Backlog (PBI - Product Backlog Items)

| PBI | User Story | Estimation (points) |
|-----|-----------|---------------------|
| 1 | En tant que visiteur, je veux voir un en-tête clair avec le nom du produit... | 1 |
| 2 | En tant que visiteur, je veux lire une brève description du produit... | 1 |
| 3 | En tant que visiteur intéressé, je veux pouvoir m'inscrire via un formulaire e-mail... | 3 |
| 4 | En tant que visiteur, je veux voir un appel à l'action (CTA) clair... | 1 |
| 5 | En tant que visiteur, je veux que la page soit responsive (mobile-first)... | 2 |
| **Total** | | **8 points** |

> 💡 *L'équipe a choisi 8 points, ce qui correspond à sa vélocité estimée pour un premier sprint (conservateur pour les débutants).*

---

### 📋 Tâches détaillées (issues techniques ou de conception)

Chaque User Story est décomposée en tâches réalisables en ≤ 1 journée.

| User Story | Tâche | Responsable | Estim. (heures) | Statut |
|-----------|------|-------------|------------------|--------|
| **1. En-tête** | Créer la structure HTML de l'en-tête (titre + logo) | Dev Front | 1h | ✅ |
| | Choisir une police lisible et appliquer les styles CSS | Designer | 1h | ✅ |
| **2. Description** | Rédiger le texte de présentation (2-4 phrases) | PO / Designer | 0.5h | ✅ |
| | Intégrer le texte dans la page avec mise en forme | Dev Front | 0.5h | ✅ |
| **3. Formulaire e-mail** | Créer le formulaire HTML (input + bouton) | Dev Front | 1h | 🟡 En cours |
| | Ajouter validation côté client (format e-mail) | Dev Front | 2h | ⏳ À faire |
| | Créer un endpoint simple (ex: avec Formspree ou mock API) | Dev Back | 2h | ⏳ À faire |
| | Afficher message de confirmation après soumission | Dev Front | 1h | ⏳ À faire |
| **4. CTA** | Rédiger le texte du CTA engageant | PO | 0.5h | ✅ |
| | Intégrer le CTA au-dessus/à côté du formulaire | Dev Front | 0.5h | ✅ |
| **5. Responsive** | Appliquer un layout mobile-first avec CSS (Flexbox/Grid) | Dev Front | 2h | ⏳ À faire |
| | Tester sur mobile (navigateur + outils DevTools) | Designer / Tester | 1h | ⏳ À faire |
| **Commun** | Créer le dépôt Git et structure de base du projet (HTML/CSS/JS) | Toute l'équipe | 1h | ✅ |
| | Définir le Definition of Done (DoD) pour le sprint | Scrum Master | 0.5h | ✅ |
| | Préparer le déploiement (ex: GitHub Pages) | Dev Back | 1h | ⏳ À faire |

> **Total heures estimées** : ~16.5h (dans la capacité de 24h → marge pour imprévus)

---

### 📌 Definition of Done (DoD) - Sprint 1

Une User Story est **"Done"** seulement si :

- ✅ Code revu (même de façon informelle en binôme)
- ✅ Fonctionne sur mobile et desktop
- ✅ Pas d'erreur JavaScript dans la console
- ✅ Formulaire soumet les données (même vers un service externe simple)
- ✅ Page déployée en ligne (ex: `https://votre-equipe.github.io/landing-alpha`)
- ✅ Testée par au moins un membre non-développeur

---

### 🗓️ Planning quotidien (exemple de Daily Scrum)

Chaque jour à 9h30, l'équipe répond à :

1. Qu'ai-je fait hier ?
2. Que vais-je faire aujourd'hui ?
3. Y a-t-il des blocages ?

> Exemple de blocage possible : *"Je n'arrive pas à connecter le formulaire à Formspree - besoin d'aide."*

---

### 🎯 Résultat attendu à la fin du Sprint

- Une **landing page live** accessible en ligne.
- Un **formulaire fonctionnel** qui collecte les e-mails.
- Une **expérience utilisable sur mobile**.
- Prêt pour la **Sprint Review** avec démo en direct !

---

Ce Sprint Backlog est volontairement **simple, concret et réaliste** pour des débutants.

Il permet de :

- Comprendre la différence entre **Product Backlog** (quoi) et **Sprint Backlog** (comment + tâches),
- Pratiquer la décomposition en tâches,
- Travailler avec un **objectif de sprint clair**,
- Appliquer un **Definition of Done**.
