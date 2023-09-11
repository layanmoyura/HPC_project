# HPC Project: Parallelized KMeans Algorithm and Performance Benchmarking

## Overview

In this project, we parallelized the KMeans machine learning algorithm and benchmarked its performance using strong scaling and weak scaling. We also developed a distributed data loader to load data in parallel to each MPI (Message Passing Interface) process.

## Contents of the Project

1. **Understanding the Algorithm and Parallel Traits:**

   We analyzed the KMeans algorithm and identified opportunities for parallelization to optimize its performance.

2. **Distributed Data Loader:**

   We developed a distributed data loader that supports the following scenarios:

   - Loading data from a single file with balanced loading among MPI processes.
   - Loading data from multiple files with varying row counts while maintaining load balance.
   - Optional: Loading data from a message broker in batches. Documentation and examples were provided for each scenario.

3. **Parallelizing the Algorithm:**

   We parallelized the KMeans algorithm to distribute the computation across multiple MPI processes for enhanced performance.

4. **Running and Benchmarking:**

   We executed the code in distributed mode and performed strong scaling and weak scaling experiments:

   - We plotted charts to visualize performance under various settings, taking into account system limitations and parallelism choices.
   - We evaluated and documented the following attributes:
     - Data loading time
     - Algorithm computation time
     - Communication time



Feel free to customize this template further to fit the specific details of your project. Markdown is a versatile format, so you can include links, images, and other elements as needed.
