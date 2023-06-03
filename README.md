# rl-testing
Toy experiments with reinforcement learning

### grid-experiments.ipynb

Contains a class for generating an arbitrary sized nxm grid with a randomly generated valley-like "landscape" of penalties, and multiple user-specified end-goal locations.

Sometimes the agent is "enclosed" in the landscape and stays refuses to cross the hill to find the main goal, so gets stuck in a "local minimum". Other times it ventures out further to find one of the main goals. Turning into an interesting exercise in experimenting with the reward function to encourage the agent to venture further.

