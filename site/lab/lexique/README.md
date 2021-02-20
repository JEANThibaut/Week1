
# Lexique du vocabulaire du Web

 Ce Fichier a pour but de répértorier les différents mots et conceptes en rapport avec l'apprentissage effectué la première semaine de formation.
Il pourra être étoffé par la suite et servira de rappel en cas de nécessité.

## Lexique

Vous trouverez ici la liste des termes employés dans le domaine du web ainsi que leurs définitions.

### git/github

- **git** : git est un logiciel de versionning permettant de sauvegarder l'historique de modification d'un projet. 
Cela permet de pouvoir rapidement identifier les différents changements effectués afin de revenir à une version précédente en cas de besoin.
Il est très utile car permet de travailler avec un système de branches, permettant à chaques développeurs du projet de travailler de manière indépendante.
	 

- **github** : Github est un logiciel et une plateforme web permettant grâce à un systeme de "pull" et de "push" de déposer les différentes versions du code des projets en cours.
	 
#### Utilisation et commandes

- **git init** : initialise la détection de git
- **git status**: Etat de git, permet de voir les modifications apporté aux fichiers
- **git add -A**: ajoutes tout les fichiers en zone de staging pour préparer un commit
- **git commit -m "message"** : procéde à un commit, c'est à dire une sauvegarde de l'historique et y ajoute un message
- **git log** : permet d'afficher la liste des commit
- **git diff** : affiche les différences entres commit
- **git branch** : voir la branche de travail
- **git branch dev** : créé une nouvelle branche dev, (le dev peut être changé par le nom souhaité)
- **git checkout dev** : quitte la branche actuelle vers la branche dev
- **git push origin dev** : envoi le commit vers github, sur le serveur origin, dans la branche dev
- **git pull origin master** : récupère depuis github, sur le serveur origin, dans la branch master
- **git merge dev** : Fusionne la branch dev dans la master

Donc pour résumé, afin de maintenir un espace de travail sur, on commence par vérifier l'état de git *(git status)*, puis on prépare les fichiers pour le commit *(git add -A)*,
on fait le commit *(git commit -m "mon message")* et on affiche les log *(git log)* pour être assuré que cela fonctionne.
Il ne reste plus qu'à faire un **push** vers git hub pour mettre à jour la branche de travail *(git push origin dev)*.
On pourra enfin faire un **pull request** depuis github afin de mettre à jour la branche master et la récupérer avec un **git pull** vers notre branche dev afin de travailler sur une branche saine.

### Le Front-End

Le front-end est la section destiné à l'affichage utilisateur, la partie graphique en somme.
Elle comprend donc le **HTML** *(HyperText Markup Launguage)*, le language permettant de créer les liens entre les pages, le **CSS** *(Cascading Style Sheets)*, le language permettant la mises en pages 
du language HTML et le **JavaScript**, un language orienté objet permettant de dynamiser les pages web.
Le développeur front-end a à disposition différents Framework (jQuery, Bootstrap...etc) lui permettant de gagné du temps dans le dévoppement.


### Le Back-End

Le back-end est la partie invisible à l'utilisateur, elle comprend les applications web, les bases de données, les serveur d'hebergements.
Pour développer cela il existe différents language, tels que **PHP**, **SQL**, **Ruby** ou encore **Python**.
Comme pour le front-end le développeur back-end peut utiliser différents Framework dans le même but visé, gagné du temps.


