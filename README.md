# CPU-GPU_Benchmarking
CPU-GPU Benchmarking


This project is about, drawing a Cube in CPU and rotate it with matrix operations in its own center at the CPU. Then making the same rotating proccess in the GPU and comparing their performances. And increase the performance at the GPU with multi-streams technique.

![image](https://user-images.githubusercontent.com/81033171/159161657-21cabca6-fb68-43f7-bfe3-2e320b5e77da.png)

*Figure 1: Front Face of Cubes. (a) Cube created for CPU. (b) Eight times subdivided version of the cube created for CPU. (c) Cube created for GPU. (d) Eight times subdivided version of the cube created for GPU.*


## V1:
A Cube object rotates 90 degree around its own center first in CPU then in GPU.

![image](https://user-images.githubusercontent.com/81033171/159161721-30e0be3c-5725-4580-9c0a-ad207819d96f.png)

*Figure 2: V1 Terminal Output*

## V2:
GPU part of the project is separated in streams that work in concurrently.

![image](https://user-images.githubusercontent.com/81033171/159161789-6ac1059b-ad81-4bf5-a322-5db9e3ca377c.png)

*(a) With Single Stream*

![image](https://user-images.githubusercontent.com/81033171/159161790-232e4a13-940a-4242-b4f6-49a4a6b11e69.png)

*(b) With Eight(8) Streams*

*Figure 3: Execution of tasks in timeline. For single stream green is copying data from host to device, red is copying data from device to host and purple is kernel launch. For eight steams green is copying data from host to device, pink is copying data from device to host and purple is kernel launch.*


![image](https://user-images.githubusercontent.com/81033171/159161730-9c7f5c34-b68f-4a2a-a7f7-b1a96454a7f3.png)

*Figure 4: V2 Terminal Output*


