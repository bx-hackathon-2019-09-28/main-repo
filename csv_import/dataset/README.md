
Problématique :
Dans différent uses cases, on a besoin de regrouper les produits selon leurs nature/tags. Ces tags sont affectés à la main quand le produit rentre dans l'assortiment.
On souhaite automatiser ce process en s'appuyant sur notre base d'apprentissage et pouvoir affecter ces tags aux nouveaux produits.

Description des données :
BARCODE : Identifiant unique du produit
DESC1: Description courte du produit destinée au client final
DESC2 : Une concaténation de plusieurs autres descriptions
BRAND_DESC : Le libéllé de la marque
Rayon : Le rayon associé au produit
Famille : La famille associée au produit
Sous_famille : La sous famille associée au produit
SEG_REF_CAPA_TYPE : Unité de vente (Kg, L ..)
CAPA_VOLUME : Volume du produit selon l'unité de vente
SANS_SUCRE : 1 si le produit est sans sucre 0 sinon
PORC : 1 si le produit contient du porc 0 sinon
SANS_GLUTEN : 1 si le produit est sans gluten 0 sinon
BIO : 1 si le produit est BIO 0 sinon
HALAL : 1 si le produit est halal 0 sinon
CASHER : 1 si le produit est casher 0 sinon
tags : une liste de tags (Target à prédire)

Résultat attendu :
Le but est de pouvoir prédire un ou plusieurs tags associés au produit. Le respect de l'ordre n'est pas obligatoire.
Il faudra retourner les nouveaux produits (test.csv) avec la liste des tags prédits.
Fichier de submission :
Barcode, tags
XXXXX, [tag1, tag2, ...]
