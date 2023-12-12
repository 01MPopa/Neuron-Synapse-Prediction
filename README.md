# Neuron-Synapse-Prediction
Using machine learning to predict whether a synapse will be formed based on axonal-dendritic proximity

## <ins>The Goal:</ins>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; When the axon of one neuron comes close to the dendrite of another neuron, we call this an <ins>axonal-dendritic proximity</ins>, or **ADP**. Every synapse results from an ADP, but not every ADP results in a synapse. When the ADP contains a synapse, we say the ADP has been ”converted” to a synapse. It is of major interest to neuroscience what rules determine whether ADP’s will convert to a synapse. In other words, what drives neurons to connect to each other, given that are within proximity (i.e. physically close enough)?
   
   -------------------------------------------------------------------------------------------------------------------------
   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The machine learning task is to predict whether an ADP results in a synapse, and is hence a binary classification problem. There are many, many more ADPs that do not result in a synapse, however, resulting
in unbalanced classes. Because of this, the competition will used the balanced accuracy metric to determine
the public and private leaderboard winners. Note that during the competition, submissions will be scored
according to the public leaderboard and the private leaderboard will only be revealed at the close of the
competition.

   -------------------------------------------------------------------------------------------------------------------------

 *This competition is part of a major ongoing research project in neuroscience. Being able to predict when
an ADP will convert to a synapse and explain why this happens, is an open problem in neuroscience and a
new solution would represent a major advance.*
