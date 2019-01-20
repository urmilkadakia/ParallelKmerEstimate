# ParallelKmerEstimate
A Streaming Algorithm for Estimating k-mer Counts with Optimal Space Usage in Parallel.

## Usage
1. **Compile:**
```
g++ -o pkmerEst parallelKmerCountEstimate.cpp -std=c++11 -O3 -march=native
```

2. **Run:**
```
./pkmerEst -f <seq.fa> -k  <kmerLen> -s <minHeap_Size> -c <coverage> -t <thread_count> -q <queue_size> -o <out.txt>
```
