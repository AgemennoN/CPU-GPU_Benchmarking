# CPU-GPU_Benchmarking
CPU-GPU Benchmarking


This project is about, drawing a Cube in CPU and rotate it with matrix operations in its own center at the CPU. Then making the same rotating proccess in the GPU and comparing their performances. And if it is possible increasing the performance at the GPU with parrallelism techniques.


V1:
A Cube object rotates 90 degree around its own center first in CPU then in GPU.

![V1](https://user-images.githubusercontent.com/81033171/147891935-2d30d2f4-ba8e-4937-bb2a-ff6917e243e1.png)

Figure 1: V1 Terminal Output

V2:
GPU part of the project is separated in streams that work in concurrently.

![8Streams test results](https://user-images.githubusercontent.com/81033171/147891937-16562ff2-a056-4747-8b5d-d59cec55c7b1.png)

Figure 2: V2 Terminal Output


