# Compact-Spanner
**Generating compact k-spanners**

Copyright (c) 2022 Maulein

This work is adapted from the work done under project "Theoretically Efficient Parallel Graph
Algorithms Can Be Fast and Scalable", presented at Symposium on Parallelism
in Algorithms and Architectures, 2018. 

GBBS: Graph Based Benchmark Suite - https://github.com/ParAlg/gbbs

Copyright (c) 2018 Laxman Dhulipala, Guy Blelloch, and Julian Shun

**Organization**

The repository contains code files for our work titled “Scalable algorithms for compact low-stretch spanners on real-world graphs". The implementations are adapted from the GBBS Suite. 

Our work includes implementations of parallel graph algorithm for producing graph spanners under the variants: MPVX_Baseline, MPVX_CompactSpanner, FGV_Baseline and FGV_CompactSpanner. The code files (Spanner.h and Spanner.cc) for these variants are located under the appropriate directories. 

**Compilation** 

Bring up the GBBS Suite (refer https://github.com/ParAlg/gbbs#readme)


Create 4 copies of the folder gbbs/benchmarks/Spanner/MPXV15/ namely;

        •	gbbs/benchmarks/Spanner/MPVX_Baseline/

        •	gbbs/benchmarks/Spanner/MPVX_CompactSpanner/

        •	gbbs/benchmarks/Spanner/FGV_Baseline/

        •	gbbs/benchmarks/Spanner/FGV_CompactSpanner/


Replace the files Spanner.h and Spanner.cc in each of these folders with the corresponding files from our repository before compiling each variant. Details for compilation are specified in README of GBBS Suite https://github.com/ParAlg/gbbs#readme

**Running code**

Details for running the code are specified in README of GBBS Suite https://github.com/ParAlg/gbbs#readme. 
