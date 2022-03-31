# README

## Initialisation de notre git :

### Settings

	git config --global user.name ""
	git config --global user.email ""
	git config --global core.editor "subl.exe --wait"

(le --wait fera attendre git dans le terminal, tant que le fichier est ouvert)

	git config --global -e

(Ouvrira dans notre editeur -ici sublime text- le .gitconfig)

	git config --global core.autocrlf X
		X = true -> Windows
		X = input -> Mac / Linux

On travaillera avec master et dev, donc ici branche serait dev et branche de depart serait master

	git branch -M <branche>

(Creation de la branche de developpement)


	git remote add <branche de depart> https://github.com/rg00656q/How-to-Git.git

(Indication de l'adresse de codage)


	git clone <url> <where to clone>

## Utilisation particuliere :

	git branch -d <branche>

(Pour supprimer une branche creee localement)


	git branch -m <branche> <renom>

(Renomme une branche en une autre)


	git fetch <branche de depart>

(Recupere les information de la branche sur github)

## Utilisation des fonctions de tous les jours :

	git X -h

(Retourne la page d'aide de la commande ciblee)

	git checkout <branche_de_dev>

(Change de branche pour celle ou on desire coder)

	git pull

(Recupere les infos sur github et met les locales a jour)

	git add <fichier>

(Ajoute un ou plusieurs fichiers a l'envoi)

	git commit -m "message du commit"

(Retirer la partie -m ouvrira un editeur de texte pour faire un message plus long)

	git push -u <branche github> <notre branche>
	
(Envoi sur la branche \<notre branche\> de Github : ici on ecrira git push -u master dev)
