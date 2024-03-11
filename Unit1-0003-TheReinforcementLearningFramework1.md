## The RL Process

![image](https://github.com/companyakis/deep-rl/assets/77589867/c557bde9-f4f4-4e8a-b741-10b128fa9c7e)

The RL Process: a loop of state, action, reward and next state

To understand the RL process, let’s imagine an agent learning to play a platform game:

![image](https://github.com/companyakis/deep-rl/assets/77589867/4a792edc-bb27-4fd9-8fd4-fd37fef82770)

![image](https://github.com/companyakis/deep-rl/assets/77589867/cf3c50df-cf46-4d32-9bc6-a078bd320836)

This RL loop outputs a sequence of state, action, reward and next state.

![image](https://github.com/companyakis/deep-rl/assets/77589867/59178f3b-75e2-4414-bcdb-cc63a9280e0f)

The agent’s goal is to maximize its cumulative reward, called the expected return.

## The reward hypothesis: the central idea of Reinforcement Learning

 Why is the goal of the agent to maximize the expected return?

Because RL is based on the reward hypothesis, which is that all goals can be described as the maximization of the expected return (expected cumulative reward).

That’s why in Reinforcement Learning, to have the best behavior, we aim to learn to take actions that maximize the expected cumulative reward.

## Markov Property

the Markov Property implies that our agent needs only the current state to decide what action to take and not the history of all the states and actions they took before.

(Türkçe kaynak: https://tr.wikipedia.org/wiki/Markov_zinciri)



