# HPC_project

In this project, we parallelized the KMeans machine learning algorithm and benchmarked its performance using strong scaling and weak scaling. We also developed a distributed data loader to load data in parallel to each MPI (Message Passing Interface) process.

Contents of the Project

1. Understanding the Algorithm and Parallel Traits:
We analyzed the KMeans algorithm and identified opportunities for parallelization to optimize its performance.

2. Distributed Data Loader:
We developed a distributed data loader that supports the following scenarios:

a. Loading data from a single file with balanced loading among MPI processes.
b. Loading data from multiple files with varying row counts while maintaining load balance.
c. Optional: Loading data from a message broker in batches. Documentation and examples were provided for each scenario.
3. Parallelizing the Algorithm:
We parallelized the KMeans algorithm to distribute the computation across multiple MPI processes for enhanced performance.

4. Running and Benchmarking:
We executed the code in distributed mode and performed strong scaling and weak scaling experiments:

a. We plotted charts to visualize performance under various settings, taking into account system limitations and parallelism choices.
b. We evaluated and documented the following attributes:
i. Data loading time
ii. Algorithm computation time
iii. Communication time
