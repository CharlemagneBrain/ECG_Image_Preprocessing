# ECG_Image_Preprocessing
Traitement des images d'électrocardiogrammes : Résultat final (Setting_up_an_ECG_Function_Pipeline.ipynb)
Traitement des images d'électrocardiogrammes pour la Prédiction de fibrillation Auriculaire 🧑‍⚕️

- Rogner l'image
- Extraction des dérivations concernées par la fibrillation auriculaire
- Transformation en nuance de gris : lissage, seuillage Otsu
- Création d'images binaires avec une bonne valeure de seuil
Passer les valeurs booléennes de l'image binaire au numérique (True/False => 0/1)
- Réunion des deux images (des deux dérivations v1 et d2) en une seule image

Nous allons nous baser sur ces images pour entrainer un modèle afin de trouver les caractéristiques essentielles à la prédiction de la fibrillation auriculaire.
Tout d'abord nous allons réflèchir à une architecture de notre modèle.
- NB : les traits verticaux présents sur l'électrocardiogramme représente du bruit qui n'a pas pu être défait malgré les opérations de traitement d'image morphologique

😊



