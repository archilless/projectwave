# projectwave
## Evolutionary Structural Optimization Algorithm based on FFT-GFIEM Solver for Inverse Design of Wave Devices

We propose a Bi-directional Evolutionary Structural Optimization (BESO) methods with a target functions based on FFT-GFIEM (Green's Function Integral Equation Method based on fast matvec (implemented using Fast Fourier Transforms)) solver. It allows to find an optimal structure in a 3D space for homogeneous objects (lenses and metallic reflectors). The derived formula of target function gradient row expedited the iterative optimization processes to predict better solution. Such examples as antennas, glass lenses, parabolic reflectors, splitters are considered. Numerical experiments show that discrete gradient algorithm converges much faster than greedy algorithm for all considered cases. The developed BESO numerical methods were implemented using CUDA (C++) parallelization. In addition, the efficiency of parallelization in CUDA (C++) was analyzed in comparison with the computation time consumptions on Numpy (Python).
