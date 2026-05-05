# 📋 Enquête de Satisfaction Employé – KoboToolbox & XLSForm

## 🎯 Objectif
Concevoir et déployer une enquête de satisfaction employé optimisée pour la collecte mobile, en utilisant KoboToolbox, le standard XLSForm et Enketo pour la saisie web.

---

## 🛠️ Outils & Technologies
- KoboToolbox (collecte de données terrain)
- XLSForm (structuration du questionnaire)
- Enketo (formulaire web interactif)

---

## 📋 Conception du formulaire

Le formulaire a été développé en respectant les bonnes pratiques XLSForm :

### 🔹 Structure
- Informations générales
- Évaluation du fonctionnement
- Management & communication
- Analyse qualitative
- Contrôle de cohérence

---

### 🔹 Types de questions utilisés
- `select_one` (choix unique)
- `select_multiple` (choix multiples)
- `integer` (valeurs numériques)
- `text` (réponses ouvertes)
- `calculate` (variables calculées)

---

### 🔹 Fonctionnalités avancées

#### ✅ Logique conditionnelle (`relevance`)
- Affichage dynamique des questions selon le niveau de satisfaction
- Analyse approfondie uniquement pour les profils à risque (passif / détracteur)

#### ✅ Contraintes de validation (`constraint`)
- Contrôle des valeurs numériques (ex : ancienneté, note globale)
- Limitation du nombre de choix (max 3 réponses)

#### ✅ Scoring automatique
- Calcul d’un score global de satisfaction
- Classification automatique :
  - Promoteur
  - Passif
  - Détracteur

---

## 📊 Logique métier RH

Le formulaire permet :
- d’évaluer la satisfaction globale des employés
- d’identifier les points de friction organisationnels
- de collecter des retours qualitatifs exploitables
- de segmenter les profils selon leur niveau de satisfaction

---

## 🌐 Déploiement

- Formulaire hébergé sur KoboToolbox
- Utilisation de Enketo pour :
  - saisie web rapide
  - accessibilité sans installation mobile

---

## 🔗 Accès au formulaire

  [Formulaire Enketo](https://ee.kobotoolbox.org/x/pgeu64OX)
  [Fihier XLSForm](Docs/Enquete_de_satisfaction_des_employes_V1.xlsx)

---

## 🚀 Valeur ajoutée du projet

- Formulaire optimisé pour usage terrain (mobile + offline)
- Structure modulaire et scalable
- Intégration de logique avancée (conditions + scoring)
- Approche orientée décision RH


