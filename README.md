# CodeBreaker - Jeu de devinette en C

## Description

CodeBreaker est un jeu console en langage C où le joueur doit deviner un nombre mystère compris entre 1 et 100.  
Le joueur choisit un niveau de difficulté qui détermine le nombre de tentatives autorisées.  
Le score commence à 100 points et diminue de 5 points à chaque tentative incorrecte.  

Le jeu propose quatre niveaux :  
- Facile (10 tentatives)  
- Moyen (5 tentatives)  
- Difficile (3 tentatives)  
- Légende (2 tentatives)  

Le but est de deviner le code mystère en un minimum de tentatives pour obtenir le meilleur score possible.  

## Fonctionnement

- Le programme génère un nombre aléatoire entre 1 et 100.  
- L'utilisateur saisit ses propositions dans la console.  
- Le programme indique si la proposition est trop grande, trop petite, ou proche du nombre mystère (différence inférieure à 5).  
- Le score diminue de 5 points à chaque erreur.  
- Le jeu s’arrête lorsque le joueur trouve le code ou lorsque les tentatives sont épuisées.  
- Le joueur peut choisir de rejouer à la fin de la partie.  

## Compilation

Pour compiler le programme, utilisez la commande (avec gcc) :

```bash
gcc -o codebreaker codebreaker.c
