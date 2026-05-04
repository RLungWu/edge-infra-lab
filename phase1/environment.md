

## 環境驗證
```bash
jetson@agx-orin-64g:~/Desktop/edge-infra-lab$ jetson_release
Software part of jetson-stats 4.3.2 - (c) 2024, Raffaello Bonghi
Jetpack missing!
 - Model: NVIDIA Jetson AGX Orin Developer Kit
 - L4T: 36.4.7
NV Power Mode[0]: MAXN
Serial Number: [XXX Show with: jetson_release -s XXX]
Hardware:
 - P-Number: p3701-0005
 - Module: NVIDIA Jetson AGX Orin (64GB ram)
Platform:
 - Distribution: Ubuntu 22.04 Jammy Jellyfish
 - Release: 5.15.148-tegra
jtop:
 - Version: 4.3.2
 - Service: Active
Libraries:
 - CUDA: 12.6.85
 - cuDNN: 9.3.0.75
 - TensorRT: 10.3.0.30
 - VPI: 3.2.4
 - Vulkan: 1.3.204
 - OpenCV: 4.8.0 - with CUDA: NO
```

```bash
etson@agx-orin-64g:~/Desktop/edge-infra-lab$ nvcc --version
nvcc: NVIDIA (R) Cuda compiler driver
Copyright (c) 2005-2024 NVIDIA Corporation
Built on Tue_Oct_29_23:53:06_PDT_2024
Cuda compilation tools, release 12.6, V12.6.85
Build cuda_12.6.r12.6/compiler.35059454_0
```