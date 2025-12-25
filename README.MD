# Schotten-Totten (Java)

Projet Java du jeu **Schotten-Totten** (mode classique + variante tactique), réalisé en Programmation Orientée Objet.

## Fonctionnalités
- Mode classique + mode tactique (cartes spéciales)
- Architecture modulaire par packages : `model`, `controller`, `view`, `ai`
- Deux niveaux d’IA :
  - **JoueurIA** : choix aléatoire contrôlé (coups légaux)
  - **JoueurIAAvance** : évaluation locale des coups via un système de score
- Interface console

## 📁 Structure du projet

- `com.schottenTotten.model`  
  Entités du jeu : `Carte`, `Borne`, `Pioche`, `Joueur`, `CombinaisonBorne`, etc.

- `com.schottenTotten.controller`  
  Logique de la partie : `Jeu`, `JeuFactory`, gestion des tours et des règles.

- `com.schottenTotten.view`  
  Interface console : `App`, `InteractionConsole`.

- `com.schottenTotten.ai`  
  Intelligence artificielle : `JoueurIA`, `JoueurIAAvance`.

---

## ▶️ Lancer le projet

### Compilation (depuis la racine du projet)

```bash
javac com/schottenTotten/**/*.java

#### Execution
```bash
java com.schottenTotten.view.App
