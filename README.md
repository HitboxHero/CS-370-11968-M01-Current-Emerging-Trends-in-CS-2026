# CS-370-11968-M01-Current-Emerging-Trends-in-CS-2026

## About
This repository is part of my ongoing CS portfolio. It showcases my work in artificial intelligence with a focus on neural networks, reinforcement learning, ethics, and real-world AI applications. Included are course discussions, assignments, and the Pirate Intelligent Agent project, where I applied deep Q-learning in a Jupyter Notebook to solve a pathfinding problem.

## Repository Contents

### Pirate Intelligent Agent (Project Two)

Summary:
This project focused on building an intelligent pirate NPC for a treasure hunt game. The pirate must navigate a maze with obstacles and find the treasure before the player. The main problem solved is pathfinding using reinforcement learning instead of hard-coded movement rules.

I was given starter code for the environment and experience replay components (TreasureMaze.py and GameExperience.py) plus a Jupyter Notebook scaffold (TreasureHuntGame.ipynb). I created and completed the Q-training algorithm section in the notebook, including the training loop, epsilon-greedy action selection, replay-based training calls, target network updates, win-rate tracking, and early stopping checks using the provided completion check function.

The final result is a deep Q-learning agent that learns from reward feedback and improves over repeated episodes. The project helped me connect reinforcement learning concepts (state, action, reward, exploration, exploitation) to a concrete game problem.

Tools and resources added to my network:
- Jupyter Notebook in Codio and local Python setup workflows
- Keras / TensorFlow for neural network modeling
- Reinforcement learning concepts from Sutton and Barto and course materials
- Debugging workflow for environment setup, dependency issues, and notebook execution

Skills transferable to other projects:
- Building and debugging training loops in Python
- Using neural networks as function approximators
- Applying reinforcement learning to sequential decision problems
- Reading starter code and extending it without breaking provided components
- Working with Jupyter notebooks for experimentation and documentation

How I made this project maintainable, readable, and adaptable:
I kept the code organized around the provided structure, used clear variable names, and added in-line comments in the Q-training section to explain each step of the learning loop. I also kept the provided .py files unchanged and only implemented logic in the notebook where the assignment required it.

---

## Course Reflection (Module Eight Journal)

### Briefly explain the work that you did on this project. What code were you given? What code did you create yourself?
For the Pirate Intelligent Agent project, I was given starter code for the maze environment and replay memory classes, plus a notebook with partial code and instructions. I did not modify the provided .py files. I created the deep Q-learning training logic in the notebook, including the episode loop, state observation flow, epsilon-greedy action selection, experience storage, replay-based training calls, target network updates, win-history tracking, and stopping logic. I also tested and debugged the notebook locally when needed and exported the final notebook as HTML for submission.

### What do computer scientists do and why does it matter?
Computer scientists design systems that solve problems using computation. That includes writing software, building models, creating algorithms, and thinking through how systems behave in the real world. It matters because software now affects almost everything, from communication and business operations to healthcare, security, and entertainment. Good computer science can make systems more efficient, more useful, and more reliable. Bad design can waste time, create risk, or harm users.

### How do I approach a problem as a computer scientist?
I approach problems by first trying to understand the real goal, constraints, and inputs before jumping into code. Then I break the problem into smaller parts and test one part at a time. In this course, that meant learning the environment, understanding the reward structure, and then implementing the training loop step by step instead of trying to solve AI all at once. I also learned that debugging setup issues (dependencies, Python versions, notebook behavior) is part of the process, not separate from it.

### What are my ethical responsibilities to the end user and the organization?
My ethical responsibility is to build systems that are safe, transparent enough for the context, and respectful of users. That means thinking about reliability, privacy, misuse, and unintended outcomes, not just whether the code runs. In this course, we talked a lot about bias, black-box behavior, and how optimization goals can create bad outcomes if they are defined poorly. For an organization, I have a responsibility to build maintainable systems and document my work clearly. For end users, I have a responsibility to avoid careless design that could harm trust, safety, or fairness.

---

## Collaborators
For this course, I have added my instructor binyam-snhu as a collaborator so they can review my portfolio work.

## Acknowledgments
Thanks to my instructor and classmates for their support and feedback throughout CS-370. This course helped me build a much stronger understanding of how AI methods actually work under the hood, especially reinforcement learning and neural networks.

## Contact
For any questions or suggestions, please feel free to open an issue or contact me.
