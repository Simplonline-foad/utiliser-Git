# Commandes Spécifiques Git

Pour pouvoir mettre le code que vous avez effectué en local sur Github, il vous faut connaître certaines commandes basiques de Git. 

Celles-ci commencent toutes par `git` :


`git init`

Commande qui initialise un nouveau dépôt Git. Seulement après avoir entré cette commande, il accepte les commandes Git qui suivent.


`git config` 

C'est un raccourci de “_configurer_”.

Ceci est tout particulièrement utile quand vous paramétrez Git pour la première fois.


`git help`

Vous avez oublié une commande ? 

Cette commande vous liste les 21 commandes les plus courues de Git. 

Vous pouvez aussi être plus spécifique et saisir “_git help init_” ou tout autre terme pour voir comment utiliser et configurer une commande spécifique git.


`git status`

Cette commande vérifie le statut de votre repository. 

Voir quels fichiers sont à l’intérieur, quels sont les changements ayant besoin d’être gardés en mémoire, et sur quelle branche du repository vous êtes en train de travailler.


`git add`

Contrairement à ce qu'on pourrait penser, cette commande n’ajoute pas de nouveaux fichiers dans votre dépôt. 

Elle porte de nouveaux fichiers à l’attention de Git. Une fois vos fichiers ajoutés, ils sont inclus dans les “_instantanés_” du dépôt Git.


`git commit`

C'est sans aucun doute la commande la plus importante de Git !

Après avoir fait toute sorte de modification, vous saisissez ça afin de prendre un “_instantané_” du dépôt. 

Généralement cela s’écrit sous la forme `git commit -m “nom de votre commit“`. Le `-m` indique que la section suivante de la commande devrait être lue comme un message.

`git branch`

Vous travaillez avec plusieurs collaborateurs et voulez produire des modifications de votre côté sans impacter le travail des autres ? 

Cette commande vous permet de construire une nouvelle branche, ou une timeline de commits, de modifications et d’ajouts de fichiers qui sont complètement les vôtres. 

Votre titre va après la commande. Par exemple, si vous vouliez créer une nouvelle branche appelée “activité-fil-rouge”, vous saisiriez git branch chats.

`git checkout` 

Cette commande permet littéralement de _rapatrier_ un dépôt dans lequel vous n’êtes pas. 

C’est une commande de navigation qui vous laisse migrer vers le répertoire que vous voulez rapatrier. 

Vous pouvez utiliser cette commande sous la forme `git checkout master` pour rapatrier la branche master, ou `git checkout activité-fil-rouge` pour rapatrier une autre branche.

`git merge`

Quand vous avez terminé de travailler sur une branche, vous pouvez fusionner vos modifications vers la branche master, qui est visible pour tous les collaborateurs. 

`git merge activité-fil-rouge` prendrait toutes les modifications que vous avez faites sur la branche “activité-fil-rouge” et les ajoutera à la la branche "master".

`git push` 

Si vous travaillez sur votre ordinateur local et que voulez que vos commits soient visibles aussi sur Github, vous _pushez_ (envoyer) les modifications vers Github avec cette commande.

git pull : Si vous travaillez sur votre ordinateur local, et su vous voulez la version la plus à jour de votre repository pour travailler dessus, vous “pull”ez (tirez) les modifications provenant de Github avec cette commande.
