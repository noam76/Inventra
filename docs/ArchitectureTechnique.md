# Architecture Technique

# StockFlow

## 1. Objectif Technique

L'objectif est de concevoir une application web légère permettant à plusieurs utilisateurs de gérer un inventaire de manière centralisée sans utiliser de base de données SQL.

Les données sont stockées dans des fichiers JSON et accessibles depuis l'application web.

L'architecture doit rester simple, modulaire et facilement maintenable.

---

## 2. Technologies Utilisées

### Front-End

- HTML5
- CSS3
- JavaScript (Vanilla)

### Stockage des Données

- JSON

### Gestion de Version

- Git
- GitHub

### Hébergement Prévu

- GitHub
- Cloudflare Workers ou solution équivalente

---

## 3. Architecture Générale

```text
Utilisateur
      │
      ▼
Navigateur Web
      │
      ▼
Interface StockFlow
      │
      ▼
Service de gestion des données
      │
      ▼
Fichiers JSON
