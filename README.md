# Pac-Man AI – Intelligent Behaviours

An AI-driven implementation of the classic Pac-Man game, developed as part of the **Intelligent Behaviours** course.

This project explores different Artificial Intelligence techniques by implementing three distinct approaches to control autonomous behaviour: **Algorithmic AI, State Machines, and Learning-Based AI using K-Nearest Neighbours (KNN).**

The main objective is to investigate how different AI methodologies can be applied to the same game environment and understand their strengths, limitations, and behavioural differences.

## Overview

Pac-Man is a classic arcade game in which the player must navigate through a maze, collect pellets, avoid enemies, and achieve the highest possible score.

In this project, different AI techniques are implemented to control the characters and make autonomous decisions within the game environment.

The project explores three different approaches to creating intelligent behaviours:

- **Algorithmic Approach:** Uses predefined rules, algorithms, and decision-making logic to determine the next actions.
- **State Machine Approach:** Implements behaviour through a set of states and transitions, allowing the AI to react differently depending on the current situation.
- **Learning-Based Approach (KNN):** Uses a K-Nearest Neighbours algorithm to make decisions based on previously collected examples and learned patterns.

## Implemented AI Techniques

### 1. Algorithmic AI

This approach relies on predefined algorithms and logical rules to control the agent's behaviour.

The AI evaluates the current game situation and determines the most appropriate action according to the implemented decision-making logic.

This approach focuses on solving problems through explicit programming rather than learning from experience.

### 2. State Machine AI

The State Machine approach models the agent's behaviour as a collection of different states, with transitions triggered by specific conditions or events.

Each state represents a particular behaviour, and the AI switches between them depending on the current situation.

For example, possible behaviours could include:

- **Chasing:** Moving towards a target or pursuing Pac-Man.
- **Fleeing:** Avoiding danger or moving away from threats.
- **Patrolling:** Following a predefined movement pattern.
- **Searching:** Exploring the environment or looking for a target.

This approach provides a structured way to manage complex behaviours and allows the AI to react dynamically to changes in the game.

### 3. Learning-Based AI – K-Nearest Neighbours (KNN)

The third approach introduces Machine Learning through the **K-Nearest Neighbours (KNN)** algorithm.

Unlike the previous approaches, this technique relies on previously collected data to make decisions.

KNN works by comparing the current game situation with similar examples from a dataset and selecting an action based on the nearest neighbours.

The general process is:

1. Observe the current state of the game.
2. Extract the relevant features describing the situation.
3. Compare the current state with previously collected examples.
4. Identify the K nearest neighbours.
5. Select the most appropriate action based on their associated decisions.

This approach explores how an agent can reproduce intelligent behaviours through data-driven decision-making rather than relying exclusively on manually defined rules.

## Project Goals and Learning Outcomes

This project was developed as part of an academic assignment for the **Intelligent Behaviours** course.

Its main educational objectives were:

- Understanding different approaches to Artificial Intelligence.
- Implementing autonomous behaviour in a game environment.
- Exploring the differences between rule-based and learning-based systems.
- Understanding how State Machines can structure complex behaviours.
- Applying K-Nearest Neighbours to a practical decision-making problem.
- Investigating the advantages and limitations of different AI techniques.

## Contributing

This project was originally developed as an academic assignment, but suggestions, improvements, and new AI implementations are always welcome.

Feel free to fork the repository and experiment with different approaches to intelligent behaviour.

## License

See the `LICENSE` file for licensing information.

Developed as part of the Intelligent Behaviours course.

*Exploring Artificial Intelligence through the classic Pac-Man game.*
