
## [Constructing Robust, High-Performance Amidar Agents (Undergraduate Research)](https://github.com/salahzoubi/High-Performance-AMIDAR-Agents)

<img src="https://media.giphy.com/media/JmhTts7Len94Pf1C2l/giphy.gif" width="600" height="350" img align="center">

This project serves as a proof-of-concept for traditionally coded Amidar agents that are capable of generalizing their game-play to different contexts. These agents employ a combination of mutually exclusive strategies to navigate their way through the Amidar environment. They are successful in beating the first level of Amidar when there are less than 3 enemies in the game and perform reasonably well when there are less than 4 enemies. Ideally, the performance of these agents will be compared to the performance of reinforcement learning agents, trained on the same task, and will provide deeper insight into explaining the actions of these reinforcement learning agents. 


[Full Article (PDF)](https://pdfhost.io/v/4neOFC73U_Constructing_HighPerformance_Amidar_Agents_using_Traditional_Programming.pdf)


## Classifiying Toxicity in Online Wikipedia Comments

<img src="https://3.bp.blogspot.com/-NUvWUOA4UUM/XcEuiroLuJI/AAAAAAAAJ1o/jPAswUodLuwn-Hc3RVhu-6xmTeB9ZfgAACLcBGAsYHQ/s1600/most-toxic-chart.png">

This project is concerned with classifiying toxicity in Wikipedia comments. It employs multiple classification techniques, such as Naive Bayes, Logistic Regression and RNN's, to detect any harmful/toxic comments. This project also proposes novel implementations in the field of NLP such as Transformers (specification is for BERT models). The classifiers achieve a classfication accuracy of 96%. 

[Full Article (PDF)](https://pdfhost.io/v/LEBGoGZbR_cs585_final_report__Copy_pdf.pdf)

## [Pacman AI Simulator (Artifical Intelligence & Reinforcement Learning)](https://github.com/salahzoubi/Pacman-AI-Simulator)

<img src="http://ai.berkeley.edu/images/pacman_game.gif">

This is a solution to the berkley AI project that is being used for a demonstration for a Math modeling class.

the following is taken from the Berkley AI project documentation:

To get started, run Gridworld in manual control mode, which uses the arrow keys:

python gridworld.py -m

You will see the two-exit layout from class. The blue dot is the agent. Note that when you press up, the agent only actually moves north 80% of the time. Such is the life of a Gridworld agent!

You can control many aspects of the simulation. A full list of options is available by running:

python gridworld.py -h

The default agent moves randomly

python gridworld.py -g MazeGrid

The following command loads your ValueIterationAgent, which will compute a policy and execute it 10 times. Press a key to cycle through values, Q-values, and the simulation. You should find that the value of the start state (V(start), which you can read off of the GUI) and the empirical resulting average reward (printed after the 10 rounds of execution finish) are quite close.

python gridworld.py -a value -i 100 -k 10

