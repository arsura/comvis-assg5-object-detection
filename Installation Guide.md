**Part 1 (Software Requirement)**
 - Anaconda (64 Bit) with Python 3.6 -> Anaconda(3-5.2.0) -> [Download](https://repo.anaconda.com/archive/)
 - CUDA 9.0 (64 Bit) -> [Download](https://developer.nvidia.com/cuda-toolkit-archive)
 - cuDNN for CUDA 9.0 -> [Download](https://developer.nvidia.com/rdp/cudnn-download)
 - Visual Studio 2015 or 2017
 
**Part 2 (Step By Step Installation)**
 - Make sure you already added path of Visual Studio 2015 or 2017 in System Variables (Edit in Environment Variables)
 
 - **Install Anaconda (64-bit) with Python 3.6 (Anaconda3–5.2.0)**
	 - Add Anaconda to the System PATH Environment Variables
	 - After Installed, Open Anaconda Prompt or Command Prompt and then create new environment	 
		 - `conda create -n myenv pip python=3.6.1 numpy scipy mkl pillow lxml cython jupyter matplotlib pandas`
	 - and then,	 
		 - `activate myenv`
		 
 - **Install CUDA 9.0 (64-bit)**
	 - *Operating System*: Window
	 - *Architecture*: x86_64
	 - *Version*: 10
	 - *Installer Type*: exe(local)
	 
   	 ***- Select all, and then download.***

	 - After downloaded, add CUDA to the System PATH Environment Variables
		 - first,
		> C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v9.0\bin
		 - second,
		> C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v9.0\libnvvp
		
- **Install cuDNN for CUDA 9.0**
	- After downloaded, Extract folder (bin, include, lib)
	- Move all folders inside (bin, include, lib) to CUDA at
		> C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v9.0

- **Install Tensorflow-gpu**
	- Open Anaconda Prompt or Command Prompt and then, activate your environment
		- do the following commands
			- `pip install --upgrade tensorflow-gpu`
			- `pip install --upgrade keras`

**See more information at** [Basic Install Tensorflow(GPU) in Window 10](https://medium.com/@chaampkub/object-detection-%E0%B9%82%E0%B8%94%E0%B8%A2%E0%B9%83%E0%B8%8A%E0%B9%89-tensorflow-gpu-%E0%B8%9A%E0%B8%99-window-10-%E0%B9%80%E0%B8%9A%E0%B8%B7%E0%B9%89%E0%B8%AD%E0%B8%87%E0%B8%95%E0%B9%89%E0%B8%99-part1-a68a450fa0ef)
