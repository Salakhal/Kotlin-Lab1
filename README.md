# Lab 1 : Math Operators & Variables en Kotlin

Ce laboratoire fait partie du cours **Fondamentaux de la programmation en Kotlin**. L'objectif est de maîtriser les bases du calcul numérique, la gestion des variables et la précision des types de données.

## 🎯 Objectifs
* Utiliser les opérateurs arithmétiques de base : `+`, `-`, `*`, `/`, `%`.
* Comprendre la **priorité des opérations** (PEMDAS) et l'usage des parenthèses.
* Manipuler des variables (`val`).
* Différencier la **division entière** de la **division décimale** (`Double`).
* Formater l'affichage des résultats.


## 📝 Contenu du Lab

### Task 1 : Opérations et Priorités
Tests sur les priorités opératoires classiques.
* **Priorité par défaut :** La multiplication est traitée avant l'addition.
* **Parenthèses :** Utilisation pour forcer un ordre de calcul spécifique.
* **Types de données :** Utilisation des nombres flottants (ex: `13530.0`) pour obtenir un résultat précis.

### Task 2 : Variables et Moyennes
Calcul d'un score total et d'une moyenne à partir de trois niveaux.
* **Version Int :** La division par un entier tronque la partie décimale.
* **Version PRO :** Division par un `Double` (ex: `3.0`) pour conserver les décimales et formatage via `%.2f` pour limiter à 2 chiffres après la virgule.

### Task 3 : Bonus Score Final
Application d'un multiplicateur de "boost" pour calculer un score final augmenté.

## Code
Le fichier `Lab1.kt` contient le code complet pour le Lab 1.

## Résultats attendus 

```
359907
141
839
11000.0
Total score = 257
Average (Int) = 85
Average (Double) = 85.67
Score boost = 1028
Final boosted score = 1285

```
<img width="917" height="338" alt="image" src="https://github.com/user-attachments/assets/0d435031-0875-4cb6-bb6a-5e7f55e954f3" />
