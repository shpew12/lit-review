# Papers to read regarding current Hausdorff distance algorithms

## [Interactive Hausdorff distance computation for general polygonal models](https://dl.acm.org/doi/abs/10.1145/1531326.1531380)
  * 2009
  * user-specified bound error
  * Voronoi subdivision
  * bounding volume hierarchy
  * cross-culling
  * discard unnecessary polygon pairs
  * cited by 102

## [A local start search algorithm to compute exact Hausdorff Distance for arbitrary point sets](https://www.sciencedirect.com/science/article/pii/S0031320317300559)
  * 2017
  * spacial locality feature of point sets
  * local start search (LSS) algorithm
  * outperforms EARLYBREAK (maintains good performance in overlap situations)
  * use space-filling Morton curve to order points (z-order curve)
  * O(m) best case; O(km) general case, where k is average number of iterations of inner loop
  * Morton code for multi dim point interleaves binary representations of the point coordinate values, then sort Morton codes
  * general idea: earlybreak earlier

## [An Efficient Algorithm for Calculating the Exact Hausdorff Distance](https://ieeexplore.ieee.org/abstract/document/7053955)
  * 2015
  * cited by 188
  * near linear complexity
  * outperforms HD algorithm based on R-trees
  * earlybreak algorithm
  * O(m) in best case, O(nm) in worst case
  * average case is near linear
  * they compare to SCAN method
  * also a branch and bound approach similar to ANN
  * interesting looking references for NN

## [An incremental Hausdorff distance calculation algorithm](https://dl.acm.org/doi/abs/10.14778/2002974.2002978)
  * 2011
  * cited by 130
  * use ANN search to find X that yields HD
  * incrementally explore & index X,Y simultaneously
  * the R-trees paper
  * looks interesting

## [An efficient computational algorithm for Hausdorff distance based on points-ruling-out and systematic random sampling](https://www.sciencedirect.com/science/article/pii/S0031320321000443)
  * 2021
  * reducing iterations of the outer loop

## [Hausdorff Distance with Outliers and Noise Resilience Capabilities](https://link.springer.com/article/10.1007/s42979-021-00737-y)
  * 2021
  * diffusion-based stopping kernels
  * trim off outliers
  * RHD (robust Hausdorff distance)
  * uses a threshold parameter and gradient

## [Algorithm to Calculate the Hausdorff Distance on Sets of Points Represented by k2-Tree](https://ieeexplore.ieee.org/abstract/document/8786338)
  * 2018
  * k2-tree for minimal storage of large sets
  * turns out this is in spanish

## [An efficient and locality-oriented Hausdorff distance algorithm: Proposal and analysis of paradigms and implementations](https://www.sciencedirect.com/science/article/pii/S003132032100176X)
  * 2021
  * "morphological"? approach
  * compares sequential and parallel computational methods
  * good for high-resolution, high-density, non-intersecting sets
  * set dilations (scaling) until it covers the other set

## [Efficient and Accurate Hausdorff Distance Computation Based on Diffusion Search](https://ieeexplore.ieee.org/abstract/document/8125673)
  * 2017
  * diffusion search
  * NN of a break in the current loop is likely near the break in subseq loops
  * Z-order HD algorithm (ZHD)
  * ZHD is not efficient for dense pt sets, so they use OHD
  * OHD (octree based HD algorithm)

## [Precise Hausdorff distance computation between polygonal meshes](https://www.sciencedirect.com/science/article/pii/S016783961000049X)
  * 2010

## [An efficient approach to directly compute the exact Hausdorff distance for 3D point sets](https://content.iospress.com/articles/integrated-computer-aided-engineering/ica544)
  * 2017
  * 3D specifically
  * 2 cases: overlapping and non-overlapping (OHD and NOHD resp.)
  * noting it outperforms EARLYBREAK in overlapping cases
  * NOHD: builds octree, then uses branch & bound and earlybreaking
  * OHD: APQ (ascending priority queue)
  * get approximate HD, build octree given AHD,
  * use a cube-to-points algorithm

## [Efficient Computation of the Hausdorff Distance Between Polytopes by Exterior Random Covering](https://link.springer.com/article/10.1007/s10589-005-4560-z)
  * 2005
  * point set to arbitrary compact set in R^d
  * they give expected running time in terms of Harmonic numbers
  * 34 pages, 28 citations

## [Optimization of the Hausdorff distance between convex polyhedrons in R3](https://www.sciencedirect.com/science/article/pii/S2405896315023423)
  * 2015

## [Fast and robust Hausdorff distance computation from triangle mesh to quad mesh in near-zero cases](https://www.sciencedirect.com/science/article/pii/S0167839618300311)
  * 2018

## [Computational Aspects of the Hausdorff Distance in Unbounded Dimension](https://arxiv.org/abs/1401.1434)
  * 2018
  * computation of HD in unbounded dimension

## [COMPUTING THE HAUSDORFF DISTANCE BETWEEN TWO SETS OF PARAMETRIC CURVES](https://www.koreascience.or.kr/article/JAKO201334064306689.page)
  * 2013
  * repeated subdivision of parameter space
  * prune subintervals
  * O(log M) accuracy O(M^(-1))

## [Translating Hausdorff is Hard: Fine-Grained Lower Bounds for Hausdorff Distance Under Translation](https://arxiv.org/abs/2101.07696)
  * 2021
  * complexity bounds of translated Hausdorff distance
