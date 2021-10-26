# designa0

Create a new repository on the command line

	git init
	git add README.md
	git commit -m "first readme"
	git remote add origin https://github.com/inscae/designa0.git
	git push -u origin master

or push an existing repository from the commande line

	git remote add origin https://github.com/inscae/designa0.git
	git push -u origin master

La configuration de `git`, exécute les deux commandes:

	git config --global user.name "Name github"
	git config --global user.email

La commande `git config --list` listera les paramètres.

Pour connître le nom d'utilisateur, tapez en ligne de commande:

	git config user.name

Pour connître l'email, tapez en ligne de commande:

	git config user.email