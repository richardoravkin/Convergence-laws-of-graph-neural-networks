# Convergence-laws-of-graph-neural-networks
My thesis for the MSc in Advanced Computer Science at the University of Oxford, submitted in Trinity 2023. 

The thesis explores how graph neural networks behave on large random graphs, and shows that under certain conditions, they converge in a probabilistic sense. 

In particular, it shows that under certain conditions, the output of a Transformer converges (in probability) to an explicitly computed limit L. This is novel result. 

In the thesis, L is only expressed in the form of an integral that does not have a closed form solution. However, this was mainly caused by my poor choice of distribution (Uniform) for the node features. 

If one assumes a Gaussian distribution (the natural choice), L can be explicitly computed for any number of layers. In fact, one can even extend this result to a transformer with Rotary Positional Encoding (RoPE). 
