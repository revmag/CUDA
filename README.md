# CUDA Learning Journey

Challenge for 100 Days of CUDA!

Hope to be consistent, will put codes implementing basic functions in CUDA. This serves as log of progress while improving my CUDA skills.

Let's get started


| Day   | Files & Summaries                                                                 |
|-------|----------------------------------------------------------------------------------|
| day1  | `printAdd.cu`: Printed indices for 1D vector, learned the concept of how GPUs run tasks in order of thread block and grid. Threads get executed in warps of 32 threads, even if the number of threads per block is higher (not sure why the number of threads in a grid is 256). |
|       | `addition.cu`: Added GPU vector by copying from CPU to GPU and then back from GPU to CPU. |
| day2  | `function.cu`: Used `__device__` function in the kernel (it calculates things on the GPU only). |
