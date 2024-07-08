This repository contains a shell script to create a new conda environment called **"tf-cuda-env"** and install TensorFlow 2.15.1 along with CUDA support on the environment in your WSL2 Ubuntu system. This will enable you train your Tensorflow Deep Learning Project faster with the help of GPU acceleration (NVIDIA only) for your TensorFlow projects. The objecetive of this shell script is that you only need to run this script and tensorflow with CUDA support will be installed already.

**Note:**

1. Install the Anaconda/Miniconda on your own, this script does not install Anaconda/Miniconda in your WSL2. You can refer to the documentation here: https://docs.anaconda.com/anaconda/install/linux/
2. Run this Script in your Ubuntu WSL2
3. If you need other Python packages on this environment just install it manually using pip
4. Make sure you have a stable internet during this installation process, because the installation will install many CuDNN packages which is quite large.

**Prerequisites**

Before running the script, ensure that you have the following prerequisites installed on your system:

1. Ubuntu 18.04 or later
2. TensorRT (Optional)
3. NVIDIA GPU Latest Driver Installed in Windows (Tested on 556.12 Laptop Driver)

**Installation Steps**

1. **Clone the repository to your Ubuntu Directory**
   ```sh
   git clone https://github.com/Blackwhite43/Tensorflow-CUDA-Install.git
   cd Tensorflow-CUDA-Install
   ```
2. **Make the script executeable**
   ```sh
   chmod +x TF-CUDA_Install.sh
   ./TF-CUDA_Install.sh
   ```
3. After finish executing the Script, open the **TF-CUDA_Check.ipynb** file in Visual Studio Code.
4. Select the installed **"tf-cuda-env"** environment
5. Run the Notebook on that environment

This conclude the installation process of Tensorflow 2.15.1 with CUDA Support.
More update will follows
