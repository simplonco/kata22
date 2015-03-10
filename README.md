#Vos propositions pour le kata année bissextile

Vous pouvez poster ici vos propositions de solutions pour le Kata année bissextile de la session 22 de la FOAD Simplon :

* à partir du répertoire `kata_leap` du profil Github de Simplon, faites un "fork" de ce répertoire sur votre propre compte Github

* dans le dossier où se trouvent votre fichier de tests et le fichier contenant votre programme, faites :
```shell
git init
git add mon_programme.rb mon_fichier_de_tests.rb
git commit -m 'Ma super proposition'
git remote add mon_nom https://github.com/mon_compte_github/kata_leap.git
git push mon_nom master
```
(remplacez évidemment ces exemples par le nom de vos fichiers dans la commande `git add`, personnalisez votre message de commit dans la commande `git commit -m`, et dans la commande `git remote add`, remplacez `mon_nom` par le nom de votre profil github, et `/mon_compte_github/` dans l'URL par l'URL correspond à votre propre compte Github).

Cette suite de commandes vous permet
1. d'initialiser le suivi par git de votre kata sur votre ordinateur,
2. d'ajouter au suivi par git les deux fichiers que vous allez soumettre,
3. d'enregistrer ("commiter") votre proposition pour le kata,
4. d'indiquer à Git le répertoire distant sur Github sur lequel vous allez envoyer ("pusher") votre code, et enfin
5. d'envoyer vos fichiers sur Github.

* puis, rendez-vous sur votre compte Github, rendez-vous dans le répertoire où vous avez envoyé vos fichiers (https://github.com/mon_compte_github/kata_leap.git). Cliquez sur le bouton vert en haut pour faire une pull request vers Simplonco (et donc nous proposer votre solution).

A vos claviers !
