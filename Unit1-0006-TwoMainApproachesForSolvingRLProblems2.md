## Policy-Based Methods

In Policy-Based methods, we learn a policy function directly.

This function will define a mapping from each state to the best corresponding action. Alternatively, it could define a probability distribution over the set of possible actions at that state.

![image](https://github.com/companyakis/deep-rl/assets/77589867/867846ac-1eb8-47bd-a7fb-2413cb658c81)

As we can see here, the policy (deterministic) directly indicates the action to take for each step.

We have two types of policies:

### Deterministic: a policy at a given state will always return the same action.

![image](https://github.com/companyakis/deep-rl/assets/77589867/1ef9c71d-48e7-4b15-88fb-044ed501f5e3)

action = policy(state)

![image](https://github.com/companyakis/deep-rl/assets/77589867/2144e75f-037b-4d73-b83d-eb492f2cb360)

### Stochastic: outputs a probability distribution over actions.

![image](https://github.com/companyakis/deep-rl/assets/77589867/f2067f9b-9c7d-41e6-af60-c3a73c8df634)

policy(actions | state) = probability distribution over the set of actions given the current state

![image](https://github.com/companyakis/deep-rl/assets/77589867/e3f2a3ac-7e87-4993-9b95-828a3c2e6bec)

Given an initial state, our stochastic policy will output probability distributions over the possible actions at that state.

![image](https://github.com/companyakis/deep-rl/assets/77589867/d126c6bd-8fc0-475b-808b-d8279e178abb)

![image](https://github.com/companyakis/deep-rl/assets/77589867/8be66f46-2132-4d3d-a9e2-4089312ee477)
