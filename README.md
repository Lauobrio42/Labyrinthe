# Labyrinthe

## English

Generation of labyrinth (different type of algorithm) with python.

To try the game, open the file 'Maze.py' it will allow you to generate a labyrinth according to your criteria:

  - Size : 
  
            'Easy' : 10 * 10
  
            'Normal': 25 * 25
            
            'Hard' : 60 * 30
            
             'Z-Hard' : 60 * 30 when moving within a radius of 10 * 10
            
  - Generation algorithm used :
  
             Fusion Aléatoire
  
             Exploration Exhaustive
                                     
             Algorithme de Prim
             
  
  - With or without tracing


Once the maze is created you can: 

      
      -You can move using the arrows (up, down, right and left)
  
      -Regenerate a new maze with the same parameters by holding down the R key
  
      -Return to the menu with the B key
  

You can also try to beat your score by clicking on 'replay' in the menu

ThePrime.pyAlgorithm, ExplorationExhaustive.py, MergeAleatory.py files are there only to generate the maze

But their declination 'Visualization' allows to visualize the generation of the labyrinth in real time

Press space to start generation to completion or hold the right arrow for step-by-step generation

The file SolutionMaze.py generates a labyrinth and finds the output path in real time

Finally, the save.csv file is the one to manage backups

-- 

## Français

Génération de labyrinthe (différents type d'algorithme) sous python.

Pour essayer le jeu, ouvrez le fichier 'Maze.py' il vous permettra de générer un labyrinthe selon vos critères :

  -Taille :

            'Easy' : 10 * 10

            'Normal': 25 * 25

            'Hard' : 60 * 30

             'Z-Hard' : 60 * 30 en se déplaçant dans un rayon de 10 * 10

  -Algorithme de génération utilisé:

             Fusion Aléatoire

             Exploration Exhaustive

             Algorithme de Prim

  -Avec ou sans tracer.


Une fois le labyrinthe créer vous pouvez:

      -Vous déplacez à l'aide des flèches (haut, bas, droite et gauche)

      -Régénérer un nouveau labyrinthe avec les mêmes paramètres en maintenant la touche R

      -Revenir au menu avec la touche B


Vous pouvez également essayer de battre votre score en cliquant sur 'replay' dans le menu.


Les fichiers AlgorithmeDePrim.py, ExplorationExhaustive.py, FusionAleatoire.py sont là uniquement pour générer le labyrinthe.

Mais leur déclinaison 'Visualisation' permet de visualiser la génération du labyrinthe en temps réel.

Appuyez sur espace pour lancer la génération jusqu'à la fin ou maintenez la flèche droite pour une génération pas à pas.


Le fichier solveMaze.py génère un labyrinthe et trouve le chemin de sortie en temps réel.


Enfin, le fichier save.csv est là pour gérer les sauvegardes.
