# GNN-Residual-Exploration

Format of file name is x_lyrs+y_skip+<parallel>
x = number of layers
y = number of layers the skip connection skips over
parallel implies if the skip connection is further passed through any convolution layers or not.

## General observation
- Fixing seed provides reproducible results
- Varying seed values obviously changes the output.
- The variance is small for simpler networks, but the variance is drastic as networks get more complicated
- Understanding how a network will perform with increasing complexity cannot be determined.
- Dataset complexity is also something to be considered.
