# Tetriste ? Arrête !

*by Anaëlle Pollart & Maxime Jaconelli* 

### - Description :

Le Tetris est un jeu qui se présente sous forme d’une matrice où des blocs de différentes formes doivent être
posés de sorte que le plateau soit gardé le plus longtemps possible non plein. L’idée est de placer chaque bloc
à l’emplacement qui permet d’éliminer un maximum de lignes et/ou de colonnes. Ces dernières sont
supprimées automatiquement lorsqu’elles sont pleines. Dans ce projet, nous souhaitons s’inspirer du Tetris et
lui créer une toute nouvelle version.
Il s’agit de partir d’un plateau à 2 dimensions de taille minimum 21 x 21 cases - dont les lignes sont désignées
par des lettres majuscules (‘A’, ‘B’ …) et les colonnes par des lettres minuscules (‘a’, ‘b’, …) - sur lequel sera
délimitée une surface de jeu valide. Cette surface de jeu valide peut prendre trois formes différentes : cercle,
losange ou triangle.

Dans ce jeu, l’utilisateur dispose d’un ensemble de blocs qu’il devra placer tour à tour sur la surface valide du
plateau en saisissant les coordonnées de l’endroit où il veut les insérer. Certains blocs à poser sont communs
aux trois formes, mais à chacune d’entre elles d’autres formes plus adaptées peuvent s’ajouter (Cf. dernière
section)

### - Liste des fichiers

- "main.py"  : programme principal appelant les fonctions du jeu contenues dans le fichier "fonctions.py".

- "functions.py" : programme contenant les différentes fonctions nécessaire au jeu.
- "block.py" : fichier python contenant les différents blocs nécessaires au jeu, sous forme de matrice.

### - Pré-requis 

- Installer Python

- Installer les différentes librairies :

  ```cmd
  pip3 install cutie
  ```

  ```
  pip3 install art
  ```

#### Exécution du programme

- Lancer le programme dans VSCode, PyCharm ou dans un terminal :

  ```
  py main.py
  ```

​	Le paramétrage du jeu débute alors

​	*Il est fortement conseillé de lire les règles du jeu avant de débuter une partie*

- Contrôle / Navigation :
  - Touche flèche du haut / du bas pour faire son choix dans les menus
  - Touche "Entrée" pour valider son choix

  

 
