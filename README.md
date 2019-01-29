### PyTorch implementation of the k-means algorithm

This code works for a dataset, as soon as it fits on the GPU. Tested for Python3 and PyTorch 1.0.0.

For simplicity, the clustering procedure stops when the clustering stops updating.
In practice, this might be too strict and should be relaxed.
