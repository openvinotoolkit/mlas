# PROJECT NOT UNDER ACTIVE MANAGEMENT #  
This project will no longer be maintained by Intel.  
Intel has ceased development and contributions including, but not limited to, maintenance, bug fixes, new releases, or updates, to this project.  
Intel no longer accepts patches to this project.  
 If you have an ongoing need to use this project, are interested in independently developing it, or would like to maintain patches for the open source software community, please create your own fork of this project.  
  
# About MLAS
MLAS is a compute library containing processor optimized GEMM kernels and platform specific threading code.

# Unit tests for MLAS
Unit tests for the SGEMM kernels are available under onnxruntime\test\mlas. These tests run over a range of inputs that then execute the various special cases for aligned and unaligned outputs. The tests have failed if any "mismatch" strings are printed.

