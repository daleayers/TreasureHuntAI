# TreasureHuntAI
Using Q-Learning to "find the treasure" on a map

In this project, I was given code that set up a Q-Learning environment, and it was my job to implement it. This meant that I was responsible for writing the code
that allowed the Q-Learning to take place. Things like, initializing the random choice that the Agent_cell uses to learn, storing the environment and episode 
states so the algorithm could evaluate them, appending a 1 for winning or a 0 for losing so we could assess a winning percentage, figuring out the correct 
ratio of epochs to batch size that would be optimal for the algorithm to solve the game as quickly as possible. 

This project utilizes Q-Learning, which is an AI concept in which Reinforcement Learning is used to solve a problem. The algorithm will start out not knowing anything
about the game; it will then start to make random choices, and depending on how the algorithm rewards or penalizes it, it will learn what to do next. This is called 
exploration and exploitation; the AI explores randomly then, depending on the reward, it exploits the path which has given it the highest reward so far. The Q-value 
is the attempt to predict which next move will return the highest reward. 

Ethical concerns when using AI are prominent. Mainly around the use of data. What kind of data are we using to train our AI, and how did we come by it? Because of the
massive amounts needed sometimes for AI the demand for data will only grow in the future. The data we train our AIs on must be ethical and high quality. Another concern
is what we are using the AI for; in this case, it's simply to find the quickest path to the treasure. I do not have the room to write a 1000-page paper on the possible 
different unethical uses of AI;
I can say that computer scientists must use their best judgment when creating AI's that their use is not unethical. A classic "I know it when I see it" example. 
