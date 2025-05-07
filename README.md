# ProjetGitetGithub

    Ce repository a été créé lors d'un projet etudiant pour tester Git et ses fonctionnalités.

    J'ajoute ces ligne pour avoir un memo sur les commande basique mais utiles pour transferer des fichiers de mon projet vers mon projet Git :

- 1ere Étape: Créer un projet git (pas grand chose a faire appart se rendre sur le site se  

connecter et cliquer sur créer un projet (donner un nom etc..)).


- 2iem Étape: Prepaper un dossier sur notre PC pour stocker les fichiers du projet. 



- 3iem Étape: Ouvrir un cmd et VS code ( ou n'importe quelle interface de code), et se mettre 

dans le repertoire du projet. (dans le CMD via la commande cd "nomdudossier", dans vs code on 

ouvre le dossier)



- 4iem Étape: Coder, faire son projet etc.. une fois es fichiers créé en utilisant la commande 

git status dans le cmd vous verez des fichiers  non tracker (en rouge), on dois les trackers avec 

la commmande git add "nom du fichier" ou git add . pour ajnouter tous les fichiers d'un coup.



- 5ieme Étape: en re-verifiant le status via git status vous verez les fichiers en vert ( pret a 

etre commit), via la commande git commit -m "donnez une info sur les modifications [ceci sert 

juste de description de ce qui a été fais dans le commit]".



- 6ieme Étape: a ce stade le cmd devrai indiquer via git statut quelque chose comme "On branch 

main

Your branch is ahead of 'origin/main' by 1 commit.
  
  (use "git push" to publish your local commits)"

il nous suffit juste d'utiliser la commande git push -u origin main (main etant la branche sur 

laquelle on push notre projet).



Petit Résumé:

-créer un projet sur git et un dossier sur le pc

-se placer dans ce dossier pour ecrire du code via votre interface de code

-utiliser les differentes commandes pour envoyer nos fichier sur github
(git add . / git commit -m "inserer desc commit"/ git push origin main)