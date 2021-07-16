In this project, we make use of reinforcement learning to make our cars park automatically.

First, we start with a parking arena of a certain place. We then use OpenCV to find the parking slots and empty slots. We store these in a .csv files for latter usage.
Next we setup a actor-critic policy for our agent to choose an action.
Using the actions, our system will try to find the rewards for each state.
We use these rewards to fillup the Q-table.
Using this Q-table we find the shortest path to the next available empty parking spots

Tools: Python libraries,Opencv
