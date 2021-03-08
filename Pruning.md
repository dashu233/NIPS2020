1. Logarithmic Pruning is All You Need

follow from 

What’s hidden in a
randomly weighted neural network?(find an untrained sub-network achieve full trained network proformence)

Proving the lottery ticket hypothesis:
Pruning is all you need(2l-depth untrained sub-network can archieve l-depth trained network, by selecting neuron carefully. Theory)

Idea: use weight decomposition to obtain log(1/\epsilon) dependency on neurons for mimic weights

2. Pruning neural networks without any data
by iteratively conserving synaptic flow

Idea: the unmatch of pruning rate and layer collapse rate doesn't match, cause the sharp degrease of proformance as pruning rate goes higher. the authors use SynFlow to make the pruning rate more 'smooth' between layers, so when pruning rate goes high, the proformance degrease slow

3. Position-based Scaled Gradient for Model Quantization and Pruning

A simple reshape of parameter space, x -> sqrt(x), the authors said it can help SGD find low bits minima (but why don't I use a large weight decay?). May need more theoritical talk

4. 

