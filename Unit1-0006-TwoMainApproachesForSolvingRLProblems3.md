## Value-based methods

In value-based methods, instead of learning a policy function, we learn a value function that maps a state to the expected value of being at that state.

The value of a state is the expected discounted return the agent can get if it starts in that state, and then acts according to our policy.

“Act according to our policy” just means that our policy is “going to the state with the highest value”.

![image](https://github.com/companyakis/deep-rl/assets/77589867/85b8b1e1-6fad-4347-aecc-caeacd1cc93d)

Here we see that our value function defined values for each possible state.

![image](https://github.com/companyakis/deep-rl/assets/77589867/8e0c3cea-293d-4847-b8ce-7e4651690ee1)

Thanks to our value function, at each step our policy will select the state with the biggest value defined by the value function: -7, then -6, then -5 (and so on) to attain the goal.

![image](https://github.com/companyakis/deep-rl/assets/77589867/00fc9235-c189-482b-8f63-45865bf19779)

![image](https://github.com/companyakis/deep-rl/assets/77589867/0e7e1a0d-a26e-45f5-887e-90b1fd288e8c)
