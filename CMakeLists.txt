# Minimum version of CMake required.
cmake_minimum_required(VERSION 2.8)

# Set the name of your project
project(parallel)

# Include macros from the ParallelUtils library
include(ParallelUtils.cmake)

##########################################################
# If using Makefiles, be sure to set CMAKE_BUILD_TYPE to # 
# select different build configurations.                 #
# Possible values:                                       #
# - RELEASE - fully optimized for speed                  #
# - DEBUG - unoptimized, with debugging symbols          #
# - RELWITHDEBUGINFO - optimized, with debugging symbols #
# - MINSIZEREL - optimized for size                      #
# - [not set] - unoptimized                              #
##########################################################


## Example MPI program
#enable_mpi_support()
#add_executable(integrate_mpi integrate_mpi.cpp)
#target_link_libraries(integrate_mpi ${MPI_CXX_LIBRARIES})

## Example OpenMP program
#enable_openmp_support()
#add_executable(integrate_omp integrate_omp.cpp)

## Example CUDA program
#enable_cuda_support()
#cuda_add_executable(bandwidthTest bandwidthTest.cu)
