# README

### Initialisation de notre git :

(On travaillera avec master et dev, donc ici branche serait dev et branche de depart serait master)

	git branch -M <branche>

(Creation de la branche de developpement)


	git remote add <branche de depart> https://github.com/rg00656q/How-to-Git.git

(Indication de l'adresse de codage)

### Utilisation particuliere :

	git branch -d <branche>

(Pour supprimer une branche creee localement)


	git branch -m <branche> <renom>

(Renomme une branche en une autre)


	git fetch <branche de depart>

(Recupere les information de la branche sur github)

### Utilisation des fonctions de tous les jours :

	git checkout <branche_de_dev>

(Change de branche pour celle ou on desire coder)

	git pull

(Recupere les infos sur github et met les locales a jour)

	git add <fichier>

(Ajoute un ou plusieurs fichiers a l'envoi)

	git commit -m "message du commit"

(Confirme les changements et sauvegarde la version du fichier)

	git push -u <branche github> <notre branche>
	
(Envoi sur la branche \<notre branche\> de Github : ici on ecrira git push -u master dev)
