Mémo SQL
Création et insertion

CREATE TABLE : permet de créer une table en définissant ses colonnes et leurs types.

INSERT INTO : permet d’ajouter une ou plusieurs lignes de données dans une table.
Requêtes de base

SELECT : permet d’afficher des données provenant d’une table.

    : permet de sélectionner toutes les colonnes d’une table.

WHERE : permet de filtrer les lignes selon une condition.

AND : permet de combiner plusieurs conditions dans un WHERE.

ORDER BY : permet de trier les résultats (ASC croissant, DESC décroissant).

LIMIT : permet de limiter le nombre de lignes affichées.
Jointures

INNER JOIN : permet de relier deux tables ayant une colonne en commun et d’afficher les lignes correspondantes.

ON : définit la condition de liaison entre deux tables lors d’une jointure.

USING : simplifie une jointure lorsque la colonne a le même nom dans les deux tables.
Calculs et renommage

+, -, *, / : opérateurs permettant d’effectuer des calculs arithmétiques.

AS : permet de renommer une colonne ou un résultat.

ROUND : permet d’arrondir un nombre.
Chaînes de caractères

|| : permet de concaténer plusieurs chaînes de caractères.

SUBSTR : permet d’extraire une partie d’une chaîne de caractères.

UPPER : permet de mettre une chaîne en majuscules.

LOWER : permet de mettre une chaîne en minuscules.

LENGTH : permet de compter le nombre de caractères d’une chaîne.

REPLACE : permet de remplacer une sous-chaîne par une autre.

INSTR : permet de trouver la position d’une sous-chaîne dans une chaîne.
Dates et heures

DATE('now') : permet d’obtenir la date du jour.

DATE('now', '+1 day') : permet de modifier une date (jours, mois, années).

STRFTIME : permet de formater une date selon un format personnalisé.
Conditions

CASE : permet d’appliquer des conditions et de retourner un résultat selon les cas.

WHEN : définit une condition à tester dans un CASE.

THEN : indique le résultat si la condition est vraie.

ELSE : indique le résultat par défaut.

END : termine la structure conditionnelle CASE.
Modification des données

UPDATE : permet de modifier des valeurs existantes dans une table.

DELETE : permet de supprimer des lignes dans une table selon une condition.
