# Exploration Interactive du Text Mining

Ce projet est une **application web éducative interactive** conçue pour enseigner et démontrer les concepts fondamentaux du **text mining** (fouille de texte). Il s'agit d'une simulation pédagogique complète qui permet aux utilisateurs de comprendre comment les machines analysent et transforment les textes en connaissances exploitables.

## Objectif Principal

Le projet répond à la question centrale : *"Comment les machines comprennent-elles nos textes ?"* en proposant une exploration pratique et visuelle des techniques de traitement automatique du langage naturel.

## Structure et Fonctionnalités

L'application est organisée en **5 modules principaux** :

### 1. Prétraitement des Textes
- **Tokenisation** : Division du texte en unités lexicales (mots, ponctuations)
- **Suppression des mots vides** : Élimination des mots fréquents sans valeur sémantique
- **Stemming (Racinisation)** : Réduction des mots à leur racine
- **Lemmatisation** : Conversion des mots à leur forme canonique

### 2. Vectorisation des Textes
- **Matrice Termes-Documents** : Représentation de la fréquence des termes
- **Calcul TF-IDF** : Pondération qui valorise les termes rares et discriminants
- **Mesures de similarité** : Similarité cosinus et distance euclidienne
- **Visualisation dans l'espace vectoriel** : Représentation graphique des documents

### 3. Clustering de Documents
- **Algorithme K-means interactif** : Regroupement automatique par similarité
- **Classification Hiérarchique Ascendante (CAH)** : Clustering hiérarchique
- **Dendrogrammes** : Visualisation des relations entre documents
- **Simulation pas à pas** : Compréhension du processus de clustering

### 4. Classification de Documents
- **Classifieur Naïve Bayes** : Classification supervisée
- **Apprentissage supervisé** : Entraînement sur des données étiquetées
- **Test de classification en temps réel** : Classification de nouveaux documents
- **Calcul des probabilités** : Explication détaillée du processus de décision

### 5. Applications Pratiques
- **Analyse de sentiment** : Détermination de l'opinion (positive, négative, neutre)
- **Extraction d'entités nommées** : Identification des personnes, lieux, organisations
- **Résumé automatique** : Génération de résumés concis
- **Détection de thèmes** : Identification des sujets principaux

## Caractéristiques Techniques

- **Interface moderne** : Utilise Tailwind CSS pour un design responsive et attrayant
- **Visualisations interactives** : Intègre Chart.js et D3.js pour des graphiques dynamiques
- **Simulations en temps réel** : Permet aux utilisateurs de tester leurs propres textes
- **Approche pédagogique** : Explications détaillées à chaque étape
- **Code JavaScript complet** : Implémentation des algorithmes de text mining

## Installation et Utilisation

### Prérequis
- Un navigateur web moderne (Chrome, Firefox, Safari, Edge)
- Aucune installation de logiciel supplémentaire requise

### Lancement
1. Clonez ou téléchargez le projet
2. Ouvrez le fichier `text-web-maning/text-web-maning/cours.html` dans votre navigateur
3. Explorez les différents modules via les onglets de navigation

### Utilisation
- **Navigation** : Utilisez les onglets pour passer d'un module à l'autre
- **Interaction** : Entrez vos propres textes dans les zones de saisie
- **Expérimentation** : Modifiez les paramètres pour voir leur impact
- **Apprentissage** : Lisez les explications accompagnant chaque démonstration

## Public Cible

Ce projet s'adresse aux :
- **Étudiants** en informatique, linguistique computationnelle, ou sciences des données
- **Enseignants** souhaitant illustrer les concepts de text mining
- **Professionnels** désirant comprendre les technologies de traitement du langage naturel
- **Curieux** intéressés par l'intelligence artificielle et le traitement automatique des textes

## Valeur Pédagogique

L'application transforme des concepts théoriques complexes en expériences interactives, permettant une compréhension intuitive des technologies qui alimentent :
- Les moteurs de recherche
- Les assistants virtuels
- Les systèmes d'analyse de l'opinion publique
- Les outils d'aide à la décision
- Les systèmes de recommandation

## Technologies Utilisées

- **HTML5** : Structure de l'application
- **CSS3 / Tailwind CSS** : Stylisation et design responsive
- **JavaScript (Vanilla)** : Logique métier et algorithmes
- **Chart.js** : Graphiques et visualisations
- **D3.js** : Visualisations avancées (dendrogrammes)

## Fonctionnalités Interactives

- **Prétraitement en temps réel** : Visualisation immédiate des étapes de nettoyage
- **Matrices dynamiques** : Affichage interactif des matrices termes-documents et TF-IDF
- **Clustering animé** : Simulation pas à pas de l'algorithme K-means
- **Classification interactive** : Test de classification avec explications détaillées
- **Analyse de sentiment** : Évaluation en temps réel du sentiment d'un texte

## Contribution

Ce projet est conçu à des fins éducatives. Les contributions pour améliorer la pédagogie, ajouter de nouvelles fonctionnalités ou corriger des bugs sont les bienvenues.

## Licence

Projet éducatif open source - Utilisation libre à des fins pédagogiques et de recherche.

---

*Exploration Interactive du Text Mining - Une simulation éducative pour comprendre comment les machines analysent nos textes*
