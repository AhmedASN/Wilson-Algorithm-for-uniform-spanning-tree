# Wilson-Algorithm-for-uniform-spanning-tree
## Tout est dans le fichier Étude théorique et implementation.ipynb 
Le fichier /Étude théorique et implementation.ipynb se compse de deux parties, le première est une étude théorique de l’algorithme de Wilson qui permet de générer un arbre couvrant suivant une loi uniforme. Quant à la deuxième, c'est une implémentation de l'algorithme en Python et deux démos (deux  grilles, carrée et triangulaire).
## Brève description de l'algorithme:

L'algorithme initialise le labyrinthe avec une cellule de départ arbitraire. Ensuite, une nouvelle cellule est ajoutée au labyrinthe, initiant une marche aléatoire. La marche aléatoire se poursuit jusqu'à ce qu'elle se reconnecte au labyrinthe existant. Cependant, si la marche aléatoire se croise elle-même, la boucle résultante est effacée avant que la marche aléatoire continue.

![](https://github.com/AhmedASN/Wilson-Algorithm-for-uniform-spanning-tree/blob/main/Grid%20and%20UST.png) 
![](https://github.com/AhmedASN/Wilson-Algorithm-for-uniform-spanning-tree/blob/main/Grid%20and%20UST2.png)
