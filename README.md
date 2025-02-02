# CUDA Learning Journey

Challenge for 100 Days of CUDA!

Hope to be consistent, will put codes implementing basic functions in CUDA. This serves as log of progress while improving my CUDA skills.

Let's get started


| Day   | Files & Summaries                                                                 |
|-------|----------------------------------------------------------------------------------|
| day1  | `printAdd.cu`: printed indices for 1d vector, learnt the concept of how GPU run tasks, in order of thread |
        |   block and grid, threads get executed in warps of 32 threads, even if number of  |
        |   threads per block is higher ( not sure then why number of threads in a grid is 256)   |
|       | `addition.cu`: added GPU vector by copying from CPU to GPU and then back from GPU to CPU |
| day2  | `function.cu`: used __device__ function in kernel ( it calculates things in GPU only)    |
