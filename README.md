# Flappy Bird NEAT AI Project

This project implements a **Flappy Bird** game using **Python**, **Pygame**, and **NEAT (NeuroEvolution of Augmenting Topologies)** AI. The AI learns to play the game by evolving through multiple generations, gradually improving its performance. The game challenges the AI to control the bird, avoiding obstacles while maximizing survival time and progress.

---

## Demo

![Flappy Bird AI Demo](https://github.com/user-attachments/assets/473d0836-2512-49ce-9fae-efb51f832f37)

---

## Features

- **Pygame:** The game engine used to build the Flappy Bird game, handling graphics, input, and game logic.
- **NEAT AI:** NeuroEvolution of Augmenting Topologies (NEAT) is used to evolve a neural network that controls the bird.
- **Dynamic Pipes:** Randomly generated pipe heights to provide variety and challenge the bird.
- **Fitness Evaluation:** The AI's performance is measured based on survival time, progress, and avoidance of obstacles.
- **Evolutionary Process:** Over generations, the AI evolves to perform better at controlling the bird and avoiding pipes.

---

## Prerequisites

Make sure you have the following installed before running the project:

- **Python 3.6+**
- **Pygame:** A cross-platform set of Python modules designed for writing video games.
- **NEAT-Python:** A Python library to implement the NEAT algorithm for evolving neural networks.

To install the necessary dependencies, use:

  ```bash
    pip install pygame neat-python
  ```
---

## How It Works

The AI in this project uses **NEAT** (NeuroEvolution of Augmenting Topologies) to evolve a neural network that controls the Flappy Bird. The neural network receives inputs such as the bird's position, the positions of pipes, and other relevant data. Based on these inputs, the network outputs an action — whether the bird should flap or not.

The AI is trained over multiple generations. Each bird controls the game using its neural network, and its performance is evaluated based on survival time and distance traveled before colliding with a pipe. Birds that survive longer and make better decisions are considered more fit and are selected for the next generation. Over time, the AI improves as it learns from previous generations' successes and failures.

The evolutionary process includes:
This project implements the NEAT (NeuroEvolution of Augmenting Topologies) algorithm to train an AI to play Flappy Bird. The AI learns how to avoid pipes and improve its gameplay over multiple generations. The implementation is based on a tutorial found on YouTube.

---

## Key Components

- **Bird Class:** This class handles the bird's movement, including flying and falling, and drawing it on the screen.
- **Pipe Class:** Manages the creation, movement, and collision detection of pipes. Pipes are randomly generated to create challenging obstacles.
- **NEAT Integration:** This connects the neural network to the bird's actions. The network evolves over generations, learning to make better decisions and control the bird effectively.
- **Fitness Evaluation:** The AI’s fitness is evaluated based on survival time and distance traveled. The better-performing AIs are selected to form the next generation of the neural network.

---

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.

We welcome any contributions that improve the project!

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Thanks to [Tech with TIM](https://www.youtube.com/c/TechwithTIM) for the tutorial that guided the development of this project.
- Pygame and NEAT-Python for providing the necessary libraries for building the game and AI.
- Python for being an excellent and easy-to-use language for AI and game development.

---

## Credits

This project was created by Advaitaflek, following a playlist on the YouTube channel [Tech with TIM](https://www.youtube.com/playlist?list=PLzMcBGfZo4-lwGZWXz5Qgta_YNX3_vLS2).

