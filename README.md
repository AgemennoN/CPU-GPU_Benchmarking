# CPU-GPU_Benchmarking
CPU-GPU Benchmarking


This project is about, drawing a Cube in CPU and rotate it with matrix operations in its own center at the CPU. Then making the same rotating proccess in the GPU and comparing their performances. And if it is possible increasing the performance at the GPU with parrallelism techniques.


V1:
A Cube object rotates 90 degree around its own center first in CPU then in GPU.

![V1 n=256 Terminal_output](https://user-images.githubusercontent.com/81033171/147654946-d4eb39cd-40f6-450e-93ef-0db36b4c6a03.png)

Figure 1: V1 Terminal Output

V2:
GPU part of the project is separated in streams that work in concurrently.

![V2 n=256 Stream=8 Terminal_output ](https://user-images.githubusercontent.com/81033171/147655292-849d0756-5e6a-48e2-a2cb-11571bef6ee8.png)

Figure 2: V2 Terminal Output


