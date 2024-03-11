A task is an instance of a Reinforcement Learning problem. We can have two types of tasks: episodic and continuing.

## Episodic task

In this case, we have a starting point and an ending point (a terminal state). This creates an episode: a list of States, Actions, Rewards, and new States.

For instance, think about Super Mario Bros: an episode begin at the launch of a new Mario Level and ends when you’re killed or you reached the end of the level.

![image](https://github.com/companyakis/deep-rl/assets/77589867/0946ca75-1d94-4209-b238-41ae4804832f)

## Continuing tasks

These are tasks that continue forever (no terminal state). In this case, the agent must learn how to choose the best actions and simultaneously interact with the environment.

For instance, an agent that does automated stock trading. For this task, there is no starting point and terminal state. The agent keeps running until we decide to stop it

![image](https://github.com/companyakis/deep-rl/assets/77589867/4df4cb76-d02a-454d-ae80-ad34163087b4)
