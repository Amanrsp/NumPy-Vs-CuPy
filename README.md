# NumPy-Vs-CuPy

This project investigates the performance comparison between NumPy (CPU-based 
computation) and CuPy (GPU-accelerated computation) for various linear algebra operations. 
Specifically, it has four key tasks: matrix-to-matrix multiplication, matrix-to-vector 
multiplication, eigenvalue computation, and singular value decomposition (SVD). The study was 
conducted using matrices of increasing size (1000x1000, 2000x2000, 3000x3000, and 
4000x4000) to analyze how each library scales with computational complexity. Execution times 
were recorded, and visual comparisons were made for the first two operations. The results 
indicate that CuPy significantly outperforms NumPy in computational efficiency, particularly for 
large-scale operations. This project highlights the potential of GPU-accelerated computing for 
scientific and engineering applications, providing a pathway for optimizing high-performance 
numerical computations. 
