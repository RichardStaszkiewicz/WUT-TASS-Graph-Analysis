# Report
## Task A
Using Pajek, analyze a “small” graph, i.e. of a size that allows the use of standard visualization and clustering algorithms.

### Preparation
For project preparation, the Pajek software was [downloaded](http://mrvar.fdv.uni-lj.si/pajek/) along with the provided [graph data](https://www.ia.pw.edu.pl/%7Emkamola/dataset-small/6.net).

### examine the order and size of the entire network, then extract the largest connected component, examine its row and size

The original graph Pajek analysis has resulted in hereby summary:
```
Number of vertices (n): 77
----------------------------------------------------------
                                       Arcs          Edges
----------------------------------------------------------
Total number of lines                     0            254
----------------------------------------------------------
Number of loops                           0              0
Number of multiple lines                  0              0
----------------------------------------------------------

Density1 [loops allowed]    = 0.08568055
Density2 [no loops allowed] = 0.08680793
Average Degree = 6.59740260
```
Therefore, the original order of the whole graph is N=77 and the size is E=254. After the extraction of the weak connected components (as the graph is undirected, it doesn't matter if we analyze strong or weak), the obtained results are as follows:
```
Weak Components of N1 [>=1] (77, comp.=1)
==============================================================================
Dimension: 77
The lowest value:  1
The highest value: 1

Frequency distribution of cluster values:

   Cluster      Freq     Freq%   CumFreq  CumFreq% Representative
 ----------------------------------------------------------------
         1        77  100.0000        77  100.0000 Myriel
 ----------------------------------------------------------------
       Sum        77  100.0000

```
The results indicate, the whole given graph is the single connected component, with same row and size as the original one.


## Task B