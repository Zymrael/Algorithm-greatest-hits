# Algorithm-greatest-hits

A collection of the greatest hits from the field of algorithm design

## Personal collection of algorithms
#### Implemented from scratch in _Python_ (definitely **not** optimized, do not blame me!)

## Graph 

#### Topology

* [Karger's Min Cut](https://github.com/Zymrael/Algorithm-greatest-hits/blob/master/graph%20algorithms/Karger's%20min%20cut.py):
  Randomized algorithm to compute the _minimum cut_ in an undirected graph. Implemented on adjacency lists, currently poorly optimized. **O(m^2)** time, **O(m)** space
  
#### Shortest paths

* 
* [Johnson's all pairs shortest paths](https://github.com/Zymrael/Algorithm-greatest-hits/blob/master/graph%20algorithms/Johnson's%20APSP/Johnson's.py): Classic algorithm for the all-pairs shortest paths in a directed graph. Uses a round of Bellman Ford's single source shortest path algorithm to find a reweighted version of the original graph without negative edges, and subsequently runs Dijkstra's **n** times. Time complexity depends on the particular implementation of Dijkstra and Bellman Ford

**Optimizations**: This particular Bellman Ford implementation uses the standard dynamic programming space optimization of remembering only the needed inputs for the recurrence. The version of Dijkstra used here is the same as the standalone version present in this repo. It does **NOT** use heaps yet, and thus its running time is not optimized. 

## Sorting

* [Merge Sort](https://github.com/Zymrael/Algorithm-greatest-hits/blob/master/sorting/MergeSort.py): Vanilla implementation of the basic _divide and conquer_ sorting algorithm. **O(n log n)** time, **O(n)** space 

* [Quick Sort](https://github.com/Zymrael/Algorithm-greatest-hits/blob/master/sorting/QuickSort.py): Randomized, in-place quick sort. **O(n log n)** time, **O(1)** space  

## Tree

## Data Structures
