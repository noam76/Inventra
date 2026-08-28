# Cahier des Charges

# StockFlow

## 1. Présentation du Projet

### Nom du projet

StockFlow

### Description

StockFlow est une application web de gestion de stock permettant de saisir, consulter et mettre à jour des quantités d'articles à partir de plusieurs postes simultanément.

L'application utilise des fichiers JSON pour le stockage des données et ne repose sur aucune base de données SQL.

L'objectif principal est de fournir une solution simple, légère et facile à maintenir, avec une interface intuitive inspirée d'un tableur de type Excel.

---

## 2. Objectifs du Projet

L'application doit permettre :

- L'ajout d'articles.
- La modification des quantités existantes.
- La suppression d'articles.
- La consultation du stock en temps réel.
- La recherche rapide d'un article.
- Le tri des données.
- La conservation d'un historique des modifications.
- L'import et l'export des données.
- L'utilisation simultanée par plusieurs utilisateurs.

---

## 3. Utilisateurs Cibles

L'application est destinée aux utilisateurs chargés de gérer un stock ou un inventaire à partir d'un navigateur web.

Aucune connaissance technique particulière ne doit être nécessaire.

---

## 4. Fonctionnalités Principales

### Gestion des articles

- Ajouter un nouvel article.
- Modifier la quantité d'un article existant.
- Supprimer un article.
- Empêcher la création de doublons.

### Consultation des données

- Affichage sous forme de tableau.
- Recherche instantanée.
- Tri des colonnes.

### Gestion de l'historique

- Enregistrer chaque modification.
- Conserver les informations associées à chaque changement.

### Importation et exportation

- Importer un fichier JSON.
- Exporter les données au format JSON.

---

## 5. Gestion des Données

Les données doivent être stockées sous forme de fichiers JSON.

Chaque article doit posséder au minimum :

- Un numéro d'article.
- Une quantité.
- Une date de mise à jour.
- Un utilisateur associé à la modification.

---

## 6. Interface Utilisateur

L'interface doit être simple, moderne et rapide.

### Affichage principal

Le tableau principal doit contenir les colonnes suivantes :

- Numéro d'article
- Quantité
- Dernière modification
- Utilisateur
- Actions

### Actions disponibles

- Ajouter
- Modifier
- Supprimer
- Rechercher
- Trier

---

## 7. Gestion des Conflits

Le système doit être conçu pour éviter la perte de données lorsque plusieurs utilisateurs effectuent des modifications simultanément.

Les modifications doivent être validées avant leur enregistrement définitif.

---

## 8. Sécurité et Validation

L'application doit :

- Vérifier les données saisies.
- Refuser les valeurs invalides.
- Empêcher les quantités incorrectes.
- Vérifier les fichiers importés avant leur traitement.

---

## 9. Compatibilité

L'application doit fonctionner sur :

- Ordinateur
- Tablette
- Smartphone

Les principaux navigateurs doivent être supportés.

---

## 10. Évolutions Futures

Les versions ultérieures pourront inclure :

- Gestion des utilisateurs.
- Gestion des rôles.
- Statistiques.
- Tableau de bord.
- Rapports avancés.
- Export Excel.
- Synchronisation avancée.

---

## 11. Critères de Réussite

Le projet sera considéré comme réussi lorsque :

- Les données sont correctement enregistrées.
- Aucun doublon n'est créé.
- Les modifications sont historisées.
- Les utilisateurs peuvent travailler simultanément.
- L'interface reste simple et intuitive.
- Les données restent cohérentes après chaque mise à jour.

---

## Statut du document

Version : 1.0

Statut : Validé pour le démarrage du projet.
