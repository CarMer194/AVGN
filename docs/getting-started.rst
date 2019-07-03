Getting started
===============

1. Execute the command: python3 setup.py install.
2. Install all dependencies in the environment:
    if you use pip: pip install requiriments.txt
    if you use conda: conda install requiriments.txt
3. Install the UMAP library manually, download the repository: https://github.com/lmcinnes/umap
    then: pip install requiriments.txt
          python3 setup.py install
4. For tensorflow, you need to install CUDA libraries and cuDNN libraries with the NVIDIA Driver:
    -For the tensorflow 1.13.1 install CUDA 10.0 in the following link: https://developer.nvidia.com/cuda-10.0-download-archive
    Select your operating system and download the archive, and execute the bash file.
    If you dont have and NVIDIA GPU, install de the graphic driver.
    -For NVIDIA cuDNN go to: https://developer.nvidia.com/cudnn create a user account and download the library, then copy the archives
    in the CUDA folder.
    -If you have an NVIDIA GPU, install the respective driver for it. You can search in the following link: https://www.nvidia.com/Download/index.aspx?lang=en-us

5. For an implementation example go to the notebook folder. Be carefull with the paths of the data input and output, every data will be required for the next steps.
