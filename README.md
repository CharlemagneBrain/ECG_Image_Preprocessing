# ECG_Image_Preprocessing
Traitement des images d'électrocardiogrammes
- Rogner l'image
- Extraction des dérivations concernées par la fibrillation auriculaire
- Transformation en nuance de gris : lissage, seuillage Otsu
- Création d'images binaires avec une bonne valeure de seuil
- Passer les valeurs booléennes de l'image binaire au numérique (True/False => 0/1) pour la suite des opérations
- Passer l'image au négatif (255 - Img)
- Transformation de la matrice représentant l'image en un vecteur numérique afin de retrouver le signal
- ***Petit Problème*** : les traits verticaux présent sur l'électrocardiogramme représente du bruit qui n'a pas pu être défait malgré les opérations de   traitement d'image morphologique

