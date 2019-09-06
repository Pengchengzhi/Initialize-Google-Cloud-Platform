# GCP
Install CUDA

GPU: NVIDIA Tesla T4
System: Ubuntu 16.04 LTS

code
sudo apt-get upgrade
sudo apt-get update
sudo apt-get install -y make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev xz-utils tk-dev valgrind cmake unrar gfortran python3-pip python3-dev python3-wheel swig git git-core htop
sudo apt-get install python3-pip python3-setuptools
sudo pip3 install --upgrade pip
sudo pip3 install numpy scipy matplotlib pandas seaborn sklearn lightgbm xgboost tqdm
https://www.nvidia.com/Download/index.aspx
wget http://us.download.nvidia.com/tesla/418.87/NVIDIA-Linux-x86_64-418.87.00.run
sudo chmod +x NVIDIA-Linux-x86_64-418.87.00.run
sudo ./NVIDIA-Linux-x86_64-418.87.00.run
sudo reboot
nvidia-smi
