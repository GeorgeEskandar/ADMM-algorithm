# ADMM-algorithm 
Implementation of an ADMM algorithm on gpu using opencl- March 2019

The Alternating Direction Method of Multipliers solves an optimization problem with good robustness. The code in main.cpp presents the algorithm with a GPU implementation. The viennacl library is used for gpu calculations along with kernel code (kernel.cl).
The algorithm is used to minimize an energy function in image processing, to reconstruct a high resolution image from multiple lower resolution images.
