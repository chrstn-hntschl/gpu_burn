# gpu_burn

A docker image around gpu_burn, a multi-GPU CUDA stress test from http://wili.cc/blog/gpu-burn.html.

I mainly use this tool (with nvidia-docker, https://github.com/NVIDIA/nvidia-docker) to test the power setup of my GPUs in order to make sure that power is enough to run all GPUs at max at the same time.

Run `nvidia-docker run --rm chrstnhntschl/gpu_burn:latest 120` to run stress test for 120 seconds (10s is default).
