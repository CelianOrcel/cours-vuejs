# Travaux pratiques 1 - Javascript

## Exercice 1 - Préparer

Préparer un fichier HTML qui correspondra à ce design:

![Le design cible](design.png)

## Exercice 2 - Dynamiser

On va animer un peu tout ça :

1. Au chargement de la page :
   - La zone rouge n'est pas affichée
   - Le bouton close est désactivé
2. Quand l'utilisateur clique sur le bouton open :
   1. La zone rouge s'affiche
   2. Le bouton close devient clickable
   3. Le bouton open est désactivé
3. Quand l'utilisateur clique sur le bouton close :
   1. La zone rouge disparait
   2. Le bouton open devient clickable
   3. Le bouton close est désactivé

## Exercice 3 - Lister

1. Au chargement de la page, faire une requête à `https://pokeapi.co/api/v2/version-group`
2. Utiliser le champ "results" de la réponse pour générer une liste des noms de jeux Pokémon à la place des boutons open et close
3. Chaque élément de la liste contient le champ "name" d'un élément de "results"

## Exercice 4 - Détailler

1. Chaque élément de la liste est cliquable
2. Au clic, on fetch l'url associée au name cliqué
3. Le résultat est injecté dans une nouvelle zone qui est affiché à la place de la zone rouge
4. Si l'utilisateur clique sur un autre nom, alors  la zone de détail est remplacée par la nouvelle
5. *Bonus : Scroller dans la liste ne fait pas défiller la zone de détail si elle est ouverte*
