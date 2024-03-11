## Rewards and the discounting

The reward is fundamental in RL because it’s the only feedback for the agent. Thanks to it, our agent knows if the action taken was good or not.

The cumulative reward at each time step t can be written as:

![image](https://github.com/companyakis/deep-rl/assets/77589867/4b2d1562-ae23-4087-9575-e325a940a6a0)
The cumulative reward equals the sum of all rewards in the sequence.

Which is equivalent to:

![image](https://github.com/companyakis/deep-rl/assets/77589867/8e836e0d-2bda-4966-b1e2-f79b662bc31c)

However, in reality, we can’t just add them like that. The rewards that come sooner (at the beginning of the game) are more likely to happen since they are more predictable than the long-term future reward.

Let’s say your agent is this tiny mouse that can move one tile each time step, and your opponent is the cat (that can move too). The mouse’s goal is to eat the maximum amount of cheese before being eaten by the cat.

![image](https://github.com/companyakis/deep-rl/assets/77589867/47320638-83f2-4e12-b9a7-3f4ac151a6a5)

As we can see in the diagram, it’s more probable to eat the cheese near us than the cheese close to the cat (the closer we are to the cat, the more dangerous it is).

Consequently, the reward near the cat, even if it is bigger (more cheese), will be more discounted since we’re not really sure we’ll be able to eat it.

To discount the rewards, we proceed like this:

1 - We define a discount rate called gamma. It must be between 0 and 1. Most of the time between 0.95 and 0.99.

The larger the gamma, the smaller the discount. This means our agent cares more about the long-term reward.

On the other hand, the smaller the gamma, the bigger the discount. This means our agent cares more about the short term reward (the nearest cheese).

2 - Then, each reward will be discounted by gamma to the exponent of the time step. As the time step increases, the cat gets closer to us, so the future reward is less and less likely to happen.

Our discounted expected cumulative reward is:

![image](https://github.com/companyakis/deep-rl/assets/77589867/1429771a-0d21-4a0d-ac91-4a87df6d34fe)



