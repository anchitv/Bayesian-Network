# Representation and Inference of Bayesian Networks







## Pruning and Pre-Processing Techniques For Inference

1. Network pruning techniques based on query structure. This technique is composed of edge and node pruning.
2. Min-fill heuristic for variable elimination, using min-degree heuristics to break ties.






## Exact Inference
Implemented the Jointree Algorithm using the Shenoy-Shaffer architecture. The steps followed:
- Convert an elimination order into a join tree
- Join Tree Transformations: Add/Merge/Remove Clusters
- Answer query based on the Join Tree.
- Set evidence






## Approximate inference
Implemented Iterative Joingraph Propagation (IJGP) algorithm. The steps followed:
* Create Bethe cluster graph and use it as join graph
* Answer query based on join graph clusters
* Set evidence







## Benchmark


The inference techniques will be compared by analysing it over Bayes net of various sizes. We have chosen the following networks to draw a contrast:

1. Small Network       :  CANCER
2. Medium Network      :  CHILD
3. Large Network       :  HAILFINDER
4. Very Large Network  :  PATHFINDER
5. Massive Network     :  MUNIN (Full Network)
