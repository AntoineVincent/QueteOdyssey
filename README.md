# QueteOdyssey

https://git-scm.com/book/fr/v1/Les-bases-de-Git-D%C3%A9marrer-un-d%C3%A9p%C3%B4t-Git


Créer un nouveau commit :

1) D'abord effectuer les modifications souhaiter au(x) fichier(s)

2) On effectue un git status afin de voir les fichiers modifiés enregistrer à ajouter

3) On utilise git add {Nom du fichier.format} 
	ou 
"*.format" si tout les fichiers modifiés sont du même format

4) ON effectue la commande git commit -m "Indiquez un message sur vos modifications"

[ 5) On peut refaire un git status pour verifier que le commit a fonctionner ]

6) On effectue un git push -u master origin
	Le -u servant à "sauvegarder" le point de depart du push pour les suivants.

Et le commit est enregistré, et publié sur GitHub dans le repository concerné.

