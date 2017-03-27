# exerciceGit
le prof a dit :) Vous devez créer un repository Git simple contenant : Un fichier nommé "README.txt" qui présente le projet; 
Au moins 2 autres fichiers de votre choix (ils peuvent contenir des scripts de code, du texte sur un projet personnel...);  
Au moins 4 commits distincts montrant l’ajout puis la modification de certains fichiers.


# Ok chef

# Et voici mon travail
# Exercice de git	

Dans ce fichier on trouvera la description de quelques fichiers contenants des commandes pour débuter avec git et github

0 - git init
Pour activer un dossier comme repository Git, il suffit de se placer dans ce dossier avec le Terminal puis d'utiliser la commande git init. 

1 - Pour gérer un repository, Git génère un index de tous les fichiers dont il doit faire le suivi. Lorsque vous créez un fichier dans un repository, vous devez donc l'ajouter à l'index Git à l'aide de la commande git add

2 - git commit -m
Lorsque vous modifiez votre repository, vous devez demander à Git d'enregistrer vos modifications en faisant un git commit. L'option-m vous permet de lui envoyer un message décrivant les modifications effectuées, ce qui s'avèrera très utile pour vous par la suite

3 - git commit -a -m
Et bien, si vous ne faites que mettre à jour un fichier que vous aviez déjà ajouté à l'index, vous pouvez condenser ces deux étapes de la façon suivante : git commit -a -m "votre commentaire"

4 - git log
Grâce à la commande  git log qui vous affiche la liste de tous les commits que vous avez réalisés ! 

5 - git checkout SHADuCommit
Lorsque vous effectuez une série de commits sur un projet, il peut vous arriver de vouloir remonter dans le temps à la recherche d'erreurs éventuelles par exemple. Pour vous positionner sur un commit donné de votre historique, il vous suffit d'utiliser la commande git checkout de la façon suivante : 

git checkout SHADuCommit

6 - git checkout master
Pour revenir à votre branche principale (au commit le plus récent), on utilise la même commande : 
git checkout master