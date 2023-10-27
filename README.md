## Pac-Man Game AI Search Algorithms

This repository contains the implementation of two search algorithms, **Breadth-First Search (BFS)** and **Depth-First Search (DFS)**, in the context of Pac-Man Game AI.

### How to Use

1. **Clone the Repository**

    ```shell
    git clone https://github.com/Yusuf-Elsayed/AI_Pacman_Game.git
    cd AI_Pacman_Game
    ```

2. **Run Pac-Man with BFS**

    To run Pac-Man using Breadth-First Search, use the following command:

    ```shell
    python pacman.py -l tinyMaze -p SearchAgent -a fn=bfs
    ```

3. **Run Pac-Man with DFS**

    To run Pac-Man using Depth-First Search, use the following command:

    ```shell
    python pacman.py -l tinyMaze -p SearchAgent
    ```

### Testing

For testing your implementation, you can use the provided testing commands:

- Run Tiny Maze with the default Search Agent (DFS):

    ```shell
    python pacman.py -l tinyMaze -p SearchAgent
    ```

- Run Medium Maze with BFS:

    ```shell
    python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
    ```

### Auto Grader

To validate your implementation, run the autograder:

```shell
python autograder.py
```

### Author

This implementation was created by **Yusuf Elsayed** ([Yusuf-Elsayed](https://github.com/Yusuf-Elsayed)).

