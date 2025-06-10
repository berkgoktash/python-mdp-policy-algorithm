# MDP Wumpus World

This project implements a Markov Decision Process (MDP) for the classic Wumpus World grid environment. It uses two core reinforcement learning algorithms:

- **Value Iteration**: Computes the optimal state values by iteratively updating based on the Bellman optimality equation.
- **Policy Iteration**: Alternates between policy evaluation and policy improvement until convergence.

The environment includes stochastic transitions and special rewards for gold, pits, and the Wumpus, and uses a 4x4 grid setup.

## Features
- Configurable discount factor (`gamma`), convergence threshold (`eta`), and maximum iterations
- Policy visualization as a grid
- Modular and easy-to-extend Python implementation

## Usage
Run from the command line with:
```bash
python wumpus_world.py --gamma 0.9 --eta 0.01 --e 100

