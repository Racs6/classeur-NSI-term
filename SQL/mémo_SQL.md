# Mémo SQL — Commandes essentielles

---

## Création et insertion de données

**CREATE TABLE** :  
Permet de créer une table en définissant ses colonnes et leurs types.

**INSERT INTO** :  
Permet d’ajouter une ou plusieurs lignes de données dans une table.

---

## Requêtes SQL de base

**SELECT** :  
Permet d’afficher des données provenant d’une table.

**\*** :  
Permet de sélectionner toutes les colonnes d’une table.

**WHERE** :  
Permet de filtrer les lignes selon une condition.

**AND** :  
Permet de combiner plusieurs conditions dans une clause `WHERE`.

**ORDER BY** :  
Permet de trier les résultats (`ASC` croissant, `DESC` décroissant).

**LIMIT** :  
Permet de limiter le nombre de lignes affichées.

---

## Jointures entre tables

**INNER JOIN** :  
Permet de relier deux tables ayant une colonne en commun.

**ON** :  
Définit la condition de liaison entre deux tables lors d’une jointure.

**USING** :  
Simplifie une jointure lorsque la colonne porte le même nom dans les deux tables.

---

## Calculs et renommage

**+ − * /** :  
Opérateurs permettant d’effectuer des calculs arithmétiques.

**AS** :  
Permet de renommer une colonne ou un résultat.

**ROUND** :  
Permet d’arrondir un nombre.

---

## Chaînes de caractères

**||** :  
Permet de concaténer plusieurs chaînes de caractères.

**SUBSTR** :  
Permet d’extraire une partie d’une chaîne de caractères.

**UPPER** :  
Permet de mettre une chaîne en majuscules.

**LOWER** :  
Permet de mettre une chaîne en minuscules.

**LENGTH** :  
Permet de compter le nombre de caractères d’une chaîne.

**REPLACE** :  
Permet de remplacer une sous-chaîne par une autre.

**INSTR** :  
Permet de trouver la position d’une sous-chaîne dans une chaîne.

---

## Dates et heures

**DATE('now')** :  
Permet d’obtenir la date du jour.

**DATE('now', '+1 day')** :
  
Permet de modifier une date (jours, mois, années).
---

## Structures conditionnelles

**CASE** :  
Permet d’appliquer un traitement conditionnel dans une requête.

**WHEN** :  
Définit une condition à tester.

**THEN** :  
Indique le résultat si la condition est vraie.

**ELSE** :  
Indique le résultat par défaut.

**END** :  
Termine la structure conditionnelle.

---

## Modification des données

**UPDATE** :  
Permet de modifier des valeurs existantes dans une table.

**DELETE** :  
Permet de supprimer des lignes dans une table selon une condition.
