# SYCL_multiblockADMM
Implementing the multi-block ADMM by sycl. The oneAPI tools are listed.


'''

source /opt/intel/oneapi/setvars.sh

mkdir build; 

cd build

cmake ..

make

'''

Intel oneAPI Math Kernel Libray

Math Kernel has been written in cmakefile

Intel VTune Profile

vtune -collect hotspots -result-dir=./test/r000hs -- ./ADMM_Solver_sycl

Intel MPI Library

MPI has been written in cmakefile

Intel oneAPI DPC++/C++ compiler

'''

cmake.

make

'''

LVMM has been written in cmakefile

oneapi::gdb

'''

gdb-oneapi ./ADMM_Solver_sycl

'''
