# Documentation du tuto github avec git


## Initialisation du depot

...bash
git init
git remote add origin SSH_REPO
...


## Rediger un commit (bonne pratique)

...

Titre du commit

Description de notre commit avec des informations  sur l'évolution du projet

...

## Envoyer un commit sur le depot distant

...
git add .
git commit -m "Titre du commit"
git push origin main

...


## Creation d'une branche

...

git checkout -b nom de la branche

...
