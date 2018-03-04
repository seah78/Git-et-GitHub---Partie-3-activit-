# Git et GitHub Partie 3 activité

# Consignes

Expliquer, avec nos propres mots, les points suivants : 

Qu'est-ce qu'un commit;
À quoi sert la commande git log;
Qu'est-ce qu'une branche.

Imaginer que l'on parle à un ami qui connaît le développement web, mais n'a jamais utilisé Git. 
Lui présenter le principe de ces concepts importants de Git.


# Activité partie 3

-- Qu'est-ce qu'un commit ?

Un commit est le moyen d'enregistrer une nouvelle version d'un fichier et de prendre en compte toutes modifications de code.
Chaque commit est identifié par une clé unique que l'on appelle sha.
Le commit permet donc d'informer chaque développeur sur la modification réalisée, par qui et quand.
La description de chaque commit doit donc être claire pour permettre à chacun de s'y retrouver.
Cela permet donc de revenir sur une version précédente du fichier sans avoir à supprimer les lignes de code manuellement.
Il faut donc réaliser un commit régulièrement à chaque modification d'un fichier avec une description claire afin de prendre en compte toutes nouvelles modifications.

-- A quoi sert la commande git log ?

La commande git log permet de lister tous les commits d'un projet. 
On retrouve pour chaque commit l'identifiant unique "sha", l'auteur du commit et son adresse mail, la date à laquelle le commit a été créé et la description du commit. 
Avec le sha, on peut se positionner sur un commit et ainsi retrouver l'état dans lequel était le projet à la date ce commit.
Cela est très pratique pour revenir sur une version précédente du projet en cas d'erreur.

-- Qu'est-ce qu'une branche ?

Une branche permet de travailler sur une copie du projet principal et donc de développer des nouvelles fonctionalités sans affecter le projet principal. 
Cela permet de mettre en place du code sur un fichier, de créer les commits correspondant, faire des essais, sans aucune modification sur la branche principale.
Dès que le fichier est fonctionnel et prêt à être déployé, on peut alors le fusionner la branche secondaire avec la branche principale (master).
Les modifications sont alors intégrées au projet principal.
Il peut donc y avoir des conflits si une modification est intervenue sur la branche principale alors que le code ajouté à la branche secondaire n'était pas terminé.
Une bonne description d'un commit est donc essentielle pour permettre une bonne résolution sur les conflits.
