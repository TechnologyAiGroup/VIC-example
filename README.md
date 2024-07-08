This repository hosts an example of training a HMM in VIC's Stage II. 

There are 65 failing chips, with their fault candidates identified by a commerical diagnosis tool. 
They are assigned to one cluster by VIC's Stage I (failure clustering). The corresponding states 
for each of the candidate can be obtained accordingly and are provided as well. 

Using the training procedure from VIC's Stage II, we calculate the model parameters, 
including the transition probability between states (A), the emission probability from states to observations (B), 
and the initial state probability distribution (𝜋).

The code for training HMM and the above calculation is available at https://github.com/TechnologyAiGroup/VIC
