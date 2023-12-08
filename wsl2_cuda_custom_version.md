1. go to https://developer.nvidia.com/cuda-toolkit-archive and locate the version {V}
2. Follow the Installation Instructions until ```sudo apt-get -y install cuda```
3. cd /etc/apt/source.list.d
4. copy the line in cuda_{V}.list
5. paste the line to cuda.list and comment the original line
6. sudo apt install cuda
7. nano ~/.bashrc and replace path for cuda
8. source ~/.bashrc
