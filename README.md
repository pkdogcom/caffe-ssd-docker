# caffe-ssd-docker
Dockerfile for [SSD version of Caffe](https://github.com/pkdogcom/caffe) using OpenCV 3.2.

# Prerequisites 
CUDA 8.0 enabled driver and 
[Nvidia-docker](https://github.com/NVIDIA/nvidia-docker)

# How to use 
```script
nvidia-docker run -ti pkdogcom/caffe-ssd caffe
```

Or in interactive mode
```script
nvidia-docker run -ti pkdogcom/caffe-ssd bash
```

