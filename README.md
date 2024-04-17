# Gnl

L'objectif est de créer une fonction qui lit une ligne terminée par un retour à la ligne depuis un descripteur de fichier donné, un fichier ou l'entrée standard.
La fonction `get_next_line` est essentielle dans de nombreux programmes impliquant la lecture de fichiers ou l'interaction avec des flux d'entrée utilisateur. Elle permet de lire une ligne à la fois, en garantissant qu'aucune donnée n'est perdue lors de la lecture successive d'appels à cette fonction.

**Lecture de ligne:** La fonction doit lire une ligne terminée par un retour à la ligne depuis un descripteur de fichier.
**Gestion de plusieurs descripteurs:** La fonction doit être en mesure de gérer plusieurs descripteurs de fichiers en parallèle.
**Gestion de l'entrée utilisateur:** La fonction doit également être capable de lire depuis l'entrée standard (saisie utilisateur) de manière transparente.
