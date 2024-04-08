**Nom :** Ted Herambert

**Groupe :** 13

**Année :** 2023-2024

**IUT Le Havre - Cours GIT**

# Compte-rendu TP3 : Travailler en équipe sur un depôt github distant

github est tres souvamment utilisé pour le travail d’équipe. Les
collaborateurs doivent d'abord relier/cloner le dépôt distant sur leur propre machine 
personnelle (Bien sûr il faut qu'ils soient invités avant qu'ils puissent
effectuer des modifications). Ensuite, chaque personne peut travailler 
separement sur une partie du projet sur leur machine personnelle et peut ensuite
tout synchroniser lorsque chaque personne aura terminé.

## Les branches

La commande `git branch` permet d'afficher les différentes branches du dépôt.

Les branches git sont utiles car elles permettent de créer une nouvelle 
fonctionnalité supplémentaire dans le code dans une branche separee de la
branche principale appelé `master` ou `main` (une fourchette dans la 
séquence des changements).

### créer une branche

La commande `git checkout -b <nom_de_la_branche>` permet de créer une nouvelle
branche (grace à l'option -b).

### Changer de branche

La commande `git checkout <nom_de_la_branche>` permet de changer de branche.

### fusionner une branche

La commande `git merge` permet de fusionner une branche avec la branche 
dans laquelle on se trouve.

Cela pemet donc par exemple d'ajouter les fonctionalite d'une branche à la 
branche principale.

