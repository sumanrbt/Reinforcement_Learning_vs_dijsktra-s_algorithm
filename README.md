# Reinforcement_Learning_vs_dijsktra-s_algorithm
A HelloWorld problem to Reinforcement 

I have worked with this project just to learn how reinforcement learning works.

The famous dijsktra's algorithm is used for finding the shortest path, given a set of weighted edges, from the source to the destination.

Here we are working on implementing the same thing using reinforcement learning, the idea is we assume the source and the destination at the begining of the training and let the agent explore the trip along any edges, by a rewarding mechanism, we find the optimum path.
You can run the Jupyter Notebook provided, it contains the exact details required in a step-by step approach.

Specially required libraries are:

* Networkx - a python library to visualise and draw graphs easily

Note that you can play around with the two algorithms and see that Dijkstras algorithm is still the best for thii simple problem in the code, in the example given in the Notebook, try finsind the shortest path from (say 7 to 5), you will observe that the Dijkstras algorithm gives you the right solution but the reinforcement learning ,ethod does not converge.
There may be ways to get the job done, but at the moment this problem has to be takn as an introduction to Qlearning.

