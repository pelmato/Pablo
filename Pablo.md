# Pablo

La règle présentée ici est une variante du [Tamalou](https://fr.wikipedia.org/wiki/Tamalou).

## 1. Présentation

Le jeu se joue avec un jeu de 52 cartes. Le nombre de joueurs peut varier de 3 à 6. Il est possible d'augmenter le nombre de joueurs en ajoutant un second jeu de 52 cartes.
But du jeu : les joueurs doivent tenter de minimiser la valeur des cartes posées devant eux.

## 2. Déroulement de la partie

Un des joueurs mélange et distribue 4 cartes par joueur face contre table de façon à former un carré devant chaque joueur. Le reste des cartes forme la pioche. Chaque joueur regarde les 2 cartes les plus proches de lui et tente de les retenir. Les autres cartes lui restent inconnues. En début de partie chaque joueur a le droit de regarder les 2 cartes les plus proches de lui jusqu'à ce qu'il pioche pour la première fois. Le joueur à gauche de celui qui a distribué commence la partie en piochant une carte. Il peut au choix :
- poser la carte dans la défausse face visible
- placer la carte dans son jeu fasse cachée à la place de n'importe quelle autre carte et placer la carte ainsi remplacée dans la défausse face visible.

C'est ensuite le tour du joueur suivant. Il a le choix soit de tirer une carte dans la pioche soit de prendre la dernière carte posée sur la défausse.

## 3. Valeur des cartes

- 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 : valeur numérique
- Valets, Dames, Rois (sauf roi de carreaux) : 10 points
- Roi de carreaux : 0 point

## 4. Pouvoir des cartes

Certaines cartes ont un pouvoir. Ce pouvoir est valable uniquement lorsque la carte vient d'être tirée de la pioche.
- 7 : le joueur place la carte dans la défausse et a le droit de regarder une carte de son jeu.
- 8 : le joueur place la carte dans la défausse et a le droit d'échanger une carte de son jeu avec une carte d'un autre joueur. Seul le joueur qui a tiré le 8 a le droit de regarder la carte échangée. L'autre joueur se retrouve donc avec une carte inconnue dans son jeu.

NB : il n'y a pas d'obligation à utiliser le pouvoir d'une carte. Les cartes à pouvoir peuvent être utilisées normalement pour leur valeur numérique.

## 5. Paires, triples, quadruples

Si avant de piocher, un joueur possède une paire dans son jeu alors il a le droit de remplacer sa paire par la carte piochée (qu'elle provienne de la pioche ou de la défausse). Il met donc sa paire dans la défausse et se retrouve avec une carte en moins. Si le joueur s'est trompé et que les deux cartes ne constituent pas une paire, il reprend ses deux cartes et conserve la carte piochée, se retrouvant finalement avec une carte supplémentaire.

__Exemple__

Un joueur possède les cartes suivantes :
```
5 3
8 5
```
Il tire alors un 4 et décide de remplacer sa paire de 5. Son jeu devient donc le suivant :
```
4 3
8
```

La même règle s'applique pour les triples et les quadruples.

## 6. Fin de la manche

Lorsqu'un joueur estime qu'il a probablement moins de points que les autres joueurs, il annonce « Pablo » juste après avoir joué et avant que le joueur suivant ne pioche. Un dernier tour est effectué et la manche prend fin quand c'est au tour de l'annonceur. On retourne ensuite les cartes et on vérifie alors si le joueur ayant dit « Pablo » a effectivement moins de points que les autres.

## 7. Décompte des points

### 7.1. Le joueur ayant dit « Pablo »

- Si le joueur a effectivement moins de points que les autres il remporte la manche et son score est un bonus de -5 points.
- Si un autre joueur avait autant ou moins de points, alors il perd la manche. Il subit alors un malus de 10 points qu'il ajoute à la valeur de ses cartes.

### 7.2. Les autres joueurs

Les autres joueurs ont pour score la valeur de leurs cartes.

## 8. Fin de la partie

La partie prend fin lorsqu'un joueur atteint ou dépasse 100 points. Le joueur ayant le moins de points est alors déclaré vainqueur.
