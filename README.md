# The Pac-Man Projects

This repository contains my solutions for the CS188 coursework from UC Berkeley. The coursework consists of three phases: Search, Multi-Agent, and Reinforcement Learning. Each phase explores different concepts and techniques in the field of artificial intelligence. The project assignments can be found on the [UC Berkeley CS188 website](https://inst.eecs.berkeley.edu/~cs188/sp22/projects).

![pacman game gif from the university course page](pacman_game.gif)

---

## Phase 1: Search

The Search phase focuses on building search agents to solve various problems. The problems include finding paths through mazes, playing a game of "Pacman" using search algorithms, and solving problems using constraint satisfaction.

### Files and Directories

- `search/`: Contains the implementation of search agents and related utilities.
- `search/search.py`: Implements various search algorithms such as depth-first search, breadth-first search, uniform cost search, and A* search.
- `search/searchAgents.py`: Contains different search-based agents, including the Pacman agent.
- `search/maze.py`: Implements classes to represent mazes and perform maze-related operations.
- `search/searchTestClasses.py`: Contains test classes for evaluating the search algorithms and agents.

---

## Phase 2: Multi-Agent

The Multi-Agent phase explores the challenges of decision-making in multi-agent environments. It involves designing agents to play the "Pacman" game in scenarios with both adversarial and cooperative agents.

### Files and Directories

- `multiagent/`: Contains the implementation of multi-agent systems and related utilities.
- `multiagent/multiAgents.py`: Implements the agents for the multi-agent scenarios in the "Pacman" game.
- `multiagent/pacman.py`: Contains classes to simulate the "Pacman" game and handle game-related operations.
- `multiagent/ghostAgents.py`: Implements different types of ghost agents in the "Pacman" game.
- `multiagent/testClassic.py`: Contains the main testing script for evaluating the multi-agent agents.

---

## Phase 3: Reinforcement Learning

The Reinforcement Learning phase focuses on developing agents that learn from interactions with their environment. The agents learn through reinforcement learning algorithms such as value iteration and Q-learning.

### Files and Directories

- `reinforcement/`: Contains the implementation of reinforcement learning algorithms and related utilities.
- `reinforcement/valueIterationAgents.py`: Implements agents that perform value iteration to solve Markov decision processes (MDPs).
- `reinforcement/qlearningAgents.py`: Implements agents that learn using Q-learning algorithms.
- `reinforcement/approximateQAgents.py`: Contains agents that use function approximation techniques to learn in larger state spaces.
- `reinforcement/analysis.py`: Provides analysis tools to evaluate the performance of the agents.

---

## Additional Files and Directories

- `data/`: Contains sample data or configurations used for testing.
- `util.py`: Implements utility functions used throughout the coursework.
- `grader.py`: Contains autograder scripts to evaluate the correctness of the implemented solutions.
- `projectX.ipynb`: Jupyter notebook files for experimentation or additional documentation.

## Running the Code

To run the code, navigate to the relevant directory (e.g., `search/`, `multiagent/`, or `reinforcement/`) and execute the Python files using a Python interpreter:

```
python search.py
```

Ensure that you have Python installed and all the necessary dependencies resolved.

## Acknowledgments

I would like to express my gratitude to UC Berkeley and the CS188 course staff for providing the coursework materials and assignments. Their effort in designing these projects has been instrumental in helping me gain a deeper understanding of artificial intelligence concepts.
