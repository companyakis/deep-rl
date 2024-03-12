Now that we learned the RL framework, how do we solve the RL problem?

In other words, how do we build an RL agent that can select the actions that maximize its expected cumulative reward?

## The Policy π: the agent’s brain

The Policy π is the brain of our Agent, it’s the function that tells us what action to take given the state we are in. So it defines the agent’s behavior at a given time.

![image](https://github.com/companyakis/deep-rl/assets/77589867/47475987-ea27-424f-912f-134820aa85b1)

Think of policy as the brain of our agent, the function that will tell us the action to take given a state

This Policy is the function we want to learn, our goal is to find the optimal policy π*, the policy that maximizes expected return when the agent acts according to it. We find this π* through training.

There are two approaches to train our agent to find this optimal policy π*:

1 -Directly, by teaching the agent to learn which action to take, given the current state: Policy-Based Methods.

2 -Indirectly, teach the agent to learn which state is more valuable and then take the action that leads to the more valuable states: Value-Based Methods.

