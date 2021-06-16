# OpenFace: an open source facial behavior analysis toolkit

this is for Ubuntu 18.40 + melodic build

## Dependencies

```bash
sudo apt update
sudo apt install libopenblas-dev libblas-dev libdlib-dev libtbb-dev
```

## Build 

```bash
git clone https://github.com/knorth55/OpenFace.git 
cd OpenFace
mkdir build
cd build
cmake -D CMAKE_CXX_COMPILER=g++ -D CMAKE_C_COMPILER=gcc -D CMAKE_BUILD_TYPE=RELEASE ..
cd build
make -j $(nproc)
sudo make install
```
