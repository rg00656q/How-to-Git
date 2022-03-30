# README

```diff
Initialisation de notre git :
```
(On travaillera avec master et dev, donc ici branche serait dev et branche de depart serait master)

	git branch -M <branche>

(creation de la branche de developpement)


	git remote add <branche de depart> https://github.com/rg00656q/How-to-Git.git

(indication de l'adresse de codage)

Utilisation particuliere :

	git branch -d <branche>

(Pour supprimer une branche creee localement)


	git branch -m <branche> <renom>

(renomme une branche en une autre)


	git fetch <branche de depart>

(recupere les information de la branche sur github)

Utilisation des fonctions de tous les jours :

	git checkout <branche_de_dev>

	git add <fichier>

	git commit -m "message du commit"

	git push -u <branche github> <notre branche>
