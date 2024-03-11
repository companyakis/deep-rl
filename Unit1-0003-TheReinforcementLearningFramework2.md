## Observations/States Space

Observations/States are the information our agent gets from the environment. In the case of a video game, it can be a frame (a screenshot). In the case of the trading agent, it can be the value of a certain stock, etc.

There is a differentiation to make between observation and state, however:

State s: is a complete description of the state of the world (there is no hidden information). In a fully observed environment.

![image](https://github.com/companyakis/deep-rl/assets/77589867/eca685ac-2a56-4f74-82e0-94b5da8455d1)

In chess game, we receive a state from the environment since we have access to the whole check board information.

Observation o: is a partial description of the state. In a partially observed environment.

![image](https://github.com/companyakis/deep-rl/assets/77589867/5be19490-b2e1-47bc-b6c6-ac639ed2cf4e)

In Super Mario Bros, we only see the part of the level close to the player, so we receive an observation.

In Super Mario Bros, we are in a partially observed environment. We receive an observation since we only see a part of the level.

![image](https://github.com/companyakis/deep-rl/assets/77589867/0842fb40-f9a1-43d0-a7b4-568803bac1bd)
