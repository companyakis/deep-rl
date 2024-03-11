## Action Space

The Action space is the set of all possible actions in an environment.

The actions can come from a discrete or continuous space:

Discrete space: the number of possible actions is finite.

![image](https://github.com/companyakis/deep-rl/assets/77589867/d4fbc13e-57f4-4251-8026-d17ef51be9e1)

In Super Mario Bros, we have only 4 possible actions: left, right, up (jumping) and down (crouching).

Continuous space: the number of possible actions is infinite.

![image](https://github.com/companyakis/deep-rl/assets/77589867/b39b51cb-a483-4a2b-8af5-9a76ba5de2b6)

A Self Driving Car agent has an infinite number of possible actions since it can turn left 20°, 21,1°, 21,2°, honk, turn right 20°…

![image](https://github.com/companyakis/deep-rl/assets/77589867/48b3a5be-afd4-4968-9dc6-ea2388b01451)

Taking this information into consideration is crucial because it will have importance when choosing the RL algorithm in the future.
