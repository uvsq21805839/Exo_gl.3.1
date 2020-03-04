# Exercice-3.1

1. Cette classe respecte-t-elle SRP ?

Non elle ne respecte pas SRP

 Pourquoi ?

Parce qu'elle a plusieurs responsabilité qui sont:

-c a l c u l S a l a i r e : calcule de salaire
-a f f i c h eCo o r d o n n e e s : affichage de coordonnees  


2. Que se passe-t-il si la méthode de calcul du salaire change ?

Si la methode de calcul du salaire change , il aura un impacte sur les classes filles (la methode affichage)

3.Que se passe-t-il si l’affichage est remplacé par le stockage dans un fichier CSV ?

Cela va supprimer les dépendances et nous seront obligé de faire la mise en jour du classe Employe.

4. Proposez une solution respectant SRP.

Ma solution serai de  séparer les deux méthodes en deux classe qui sont: une classe qui calcul le salaire et une autre qui fait l'affichage.