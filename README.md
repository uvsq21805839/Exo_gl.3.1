# Exo_gl.3.1

exo 3.1
1) Cette classe ne respecte pas SRP car elle a plusieurs responsabilité qui sont: l'affichage(afficheCordonnees et le calcul(calculSalaire).

2) Si la méthode de calcul du salaire change:   la méthode afficheCordonnees  peut etre perturbé.

3) Si la méthode d'affichge est remplacé par le stockage dans dans un fichier CSV:  la méthode calculSaire serait modifiée aussi ET Cela va supprimer les dépendances .

4) Une des solutions possible c'est de séparer les deux méthodes en deux classe: une classe qui calcul et une autre qui fait l'affichage.
