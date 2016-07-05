# GPUTest
Detecting GPU Installation

From NVIDIA <a href="">DevBlog</a>. Run

		nvcc -o test_cuda test_cuda.cu 
		./test_cuda

It should print out something similar to

		Number of devices found: 1
		Device Number: 0
		  Device name: GeForce GT 750M
		  Memory Clock Rate (KHz): 2508000
		  Memory Bus Width (bits): 128
		  Peak Memory Bandwidth (GB/s): 80.256000
