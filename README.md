# OC Data Scientist - Projet 6 : Classifiez automatiquement des biens de consommation


## Contexte

"Place de marché” souhaite lancer une marketplace e-commerce. Sur la place de marché, des vendeurs proposent des articles à des acheteurs en postant une photo et une description.
Pour l'instant, l'attribution de la catégorie d'un article est effectuée manuellement par les vendeurs, et est donc peu fiable. De plus, le volume des articles est pour l’instant très petit.

Pour rendre l’expérience utilisateur des vendeurs (faciliter la mise en ligne de nouveaux articles) et des acheteurs (faciliter la recherche de produits) la plus fluide possible, et dans l'optique d'un passage à l'échelle, il devient nécessaire d'automatiser cette tâche.

Place du Marché souhaite étudier la faisabilité d'un moteur de classification des articles en différentes catégories, avec un niveau de précision suffisant. Je dois analyser le jeu de données en réalisant un prétraitement des descriptions des produits et des images, une réduction de dimension, puis un clustering.


## Données

https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Textimage+DAS+V2/Dataset+projet+pre%CC%81traitement+textes+images.zip


## Missions

Afin d’extraire les features texte, il sera nécessaire de mettre en œuvre :

- deux approches de type “bag-of-words”, comptage simple de mots et Tf-idf ;
- une approche de type word/sentence embedding classique avec Word2Vec (ou Glove ou FastText) ;
- une approche de type word/sentence embedding avec BERT ;
- une approche de type word/sentence embedding avec USE (Universal Sentence Encoder)

Il est fournit un exemple de mise en œuvre des approches demandées pour le traitement des features texte sur un autre dataset et on m’invite à l’utiliser comme point de départ.

Afin d’extraire les features image, il sera nécessaire de mettre en œuvre :

un algorithme de type SIFT / ORB / SURF ;
un algorithme de type CNN Transfer Learning.


## Livrables

1. Notebook contenant le pré-traitement des données texte et images ainsi que le résultat du clustering
-  DeRosa_Sebastien_1_notebook_072022.ipynb

2. Documentation du projet
-  DeRosa_Sebastien_2_presentation_072022.pdf : support de présentation qui présente la démarche et les résultats du clustering
