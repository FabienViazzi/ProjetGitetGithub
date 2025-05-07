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
(git add . / git commit -m "inserer desc commit"/ git push -u origin main)




Deuxieme partie : les Branches.

  Creation d'une branche :
    
    On peut créer une branche (au depart on est sur la branche main).

    pour cela il suffit simplement d'utiliser la commande "git branch [nomdelabranche]"

    généralement on a la branche main pour le code "fini" et la branche develop pour 

    eviter de modifier le code qui fonctionne qu'on aurai push dans le main

  Pousser la branche sur git :

    cette étape permet de partager votre travail avec d'autre developpers en 
    
    poussant la branche sur le repo distant.

    Pour cela on utilisera "git push -u origin [nomdelabranche]".

    Grâçe a cela on créer notre branche sur github et la lie a la branche local.

  Faire des modifications sur la branche :

    Il faut premièrement ce placer sur la branche que l'on souhaite modifier via "git checkout [nomdelabranche]".

    puis comme pour un fichier on va l'add -> commit -> push les données.

  Fusionner deux branches : 

    Pour fusionner deux branches on se place d'abord sur la branche qui dois recevoir les nouvelles données (ex: is on a la branceh main
    
    et develop et qu'on souhaite ajouter des fonctionnalitées qui foncitonne dans la branche main on se place sur la branche main via 
    
    "git checkout main").

    Ensuite on utilise la commande "git merge  [branche a fusionner] (ici develop).

    Enfin on commit pour finaliser la fusion : git commit -m "Fusion de la branche develop sur la branche main" et on push sur la branche 
    
    main.

    résumé :

      - On peut créer une branche via git branch "nom".

      - On peut modifier des données des fichiers sur la branche qu'on créer en ce positionnant dessus : git checkout "nom".

      - On fait ensuite notre add commit et push classique pour l'envoyer dans le depot distant.

      - On peut enfin fusionner les branches , ce placer sur la branche qui va recevoir et faire "git merge nom (ici develop)"

      - on peut commit pour preciser l'interet du merge et push pour finaliser la fusion








