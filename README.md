# PacMan
**Udacity - Artificial Intelligence Nanodegree Program**
AI - Search Algorithms applied to the PacMan Game

# Pacman
Berkeley University Project: Pacman agent will find paths through his maze world, both to reach a particular location and to collect food efficiently. You will build general search algorithms and apply them to Pacman scenarios.

![Pacman](pacman.jpg)

This project is part of **Udacity´s Artificial Intelligence Nanodegree Program**. Here you will find my personal solution to the challenge. I first explain how you can download it and test it. Next, I have added Udacity´s original instructions for completing the project

## Project Requirements
To fully test the project, you might need to install some required packages. Please start by downloading **Anaconda** using the following link: [Download Anaconda](https://www.continuum.io/downloads). Once installed, clone this repository and access the downloaded folder through a **terminal** window. Next, you need to install the required packages:

    $ conda env create -f pmaienv.yml
    
Once all the packages have been installed, activate the environment:

    $ source activate pmaienv
    
Once finished, you can run my personal version of this project

     (pmaienv)$ python pacman.py
    
You can run the program with different options, try the help to see more options

     (pmaienv)$ python pacman.py -h
     
If you want, here are some ideas:

    python pacman.py
    python pacman.py --layout testMaze --pacman GoWestAgent
    python pacman.py --layout tinyMaze --pacman GoWestAgent
    python pacman.py -h
    python pacman.py -l tinyMaze -p SearchAgent -a fn=tinyMazeSearch
    python pacman.py -l tinyMaze -p SearchAgent
    python pacman.py -l mediumMaze -p SearchAgent
    python pacman.py -l bigMaze -z .5 -p SearchAgent
    python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
    python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5
    python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs
    python pacman.py -l mediumDottedMaze -p StayEastSearchAgent
    python pacman.py -l mediumScaryMaze -p StayWestSearchAgent
    python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic 
    python pacman.py -l tinyCorners -p SearchAgent -a fn=bfs,prob=CornersProblem
    python pacman.py -l mediumCorners -p AStarCornersAgent -z 0.5
    python pacman.py -l testSearch -p AStarFoodSearchAgent
    python pacman.py -l trickySearch -p AStarFoodSearchAgent
    python pacman.py -l bigSearch -p ClosestDotSearchAgent -z .5 
    python pacman.py -l bigSearch -p ApproximateSearchAgent -z .5 -q 
    
Specially interesting, an 8 puzzle solver:

    python eightpuzzle.py

--------------------------------------------------------------------
--------------------------------------------------------------------
