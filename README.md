# ceres_example

# install ceres
```
# CMake
sudo apt-get install cmake
# google-glog + gflags
sudo apt-get install libgoogle-glog-dev libgflags-dev
# Use ATLAS for BLAS & LAPACK
sudo apt-get install libatlas-base-dev
# Eigen3
sudo apt-get install libeigen3-dev
# SuiteSparse (optional)
sudo apt-get install libsuitesparse-dev

git clone https://ceres-solver.googlesource.com/ceres-solver
cd ceres-solve
mkdir build
cd build
cmake ..
make
sudo make install
```