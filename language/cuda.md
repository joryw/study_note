# cuda

### 1.`__device__`：用于指定该函数在设备上执行

```
  __device__ Pack() {
    // do nothing
  }
```

### 2.cuda学习地址

1.cuda大师班

2.reduction

3.element-wise

4.GEMM

5.https://docs.nvidia.com/cuda/cuda-c-programming-guide/#programming-model

### 3.什么是 Shared Memory

![image-20230826160337617](../../imgs/cuda/image-20230826160337617.png)

### 4.TILE_K

![image-20230826160851073](../../imgs/cuda/image-20230826160851073.png)

### 5.shared memory中的bank conflict

![image-20230826162856911](../../imgs/cuda/image-20230826162856911.png)