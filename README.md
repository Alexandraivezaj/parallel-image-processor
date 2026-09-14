# Parallel Image Processor

A C++ image processing project that compares different approaches to parallel computing. The same image processing tasks are implemented using a serial version, OpenMP, MPI, and CUDA to compare performance across different image sizes.

## Implementations

- **Serial** — baseline implementation used for comparison
- **OpenMP** — CPU multithreading
- **MPI** — distributed parallel processing
- **CUDA** — GPU parallel processing

## Image Processing

The project uses OpenCV to load, process, and save images. Image processing operations include:

- Gaussian blur
- Canny edge detection
- Processing across multiple image sizes
- Runtime measurement and performance comparison

## Technologies

- C++
- OpenCV
- CUDA
- OpenMP
- MPI
- CMake
- Git & GitHub

## Project Structure

```text
parallel-image-processor/
├── base/       # Serial implementation
├── cuda/       # CUDA GPU implementation
├── mpi/        # MPI implementation
├── openmp/     # OpenMP implementation
├── data/       # Input data
├── results/    # Performance results
└── CMakeLists.txt
