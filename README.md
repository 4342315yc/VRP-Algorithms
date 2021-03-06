A collection of algotihms, links and paper and (naive) implementation

# VRP Algorithms

A collection of VRP algorithms. Refer to [this page](https://github.com/4342315yc/VRP-Algorithms/blob/master/References.md) for (all?) references used in this repo.

The following is the overview algorithms based on [NEO](http://neo.lcc.uma.es/vrp/solution-methods/). Note that the follwing image is just a simplified version of the overview of VRP family. The actual variants and algorithms are actually more than the following.

![Overview](https://github.com/4342315yc/VRP-Algorithms/blob/master/Images/VRP_Overview.png)

## Variants
* [CVRP](https://github.com/4342315yc/VRP-Algorithms/blob/master/Variants/README.md#capacitated-vrpcvrp)
* [VRPTW](https://github.com/4342315yc/VRP-Algorithms/blob/master/Variants/README.md#vrp-with-time-windowvrptw)
* [SVRP](https://github.com/4342315yc/VRP-Algorithms/blob/master/Variants/README.md#stochastic-vrpsvrp)
* [VRPPPD](https://github.com/4342315yc/VRP-Algorithms/blob/master/Variants/README.md#vrp-with-pick-up-and-deliveringvrppd)
* [VRPB](https://github.com/4342315yc/VRP-Algorithms/blob/master/Variants/README.md#vrp-with-backhaulsvrpb)
* [SDVRP](https://github.com/4342315yc/VRP-Algorithms/blob/master/Variants/README.md#stochastic-vrpsvrp)
* [MDVRP](https://github.com/4342315yc/VRP-Algorithms/blob/master/Variants/README.md#multiple-depot-vrpmdvrp)

## Exact Algorithms
* [Branch and bound](https://github.com/4342315yc/VRP-Algorithms/tree/master/Exact)
* [Branch and cut](https://github.com/4342315yc/VRP-Algorithms/tree/master/Exact)

## Heuristic Algorithms

Note that the following hyperlinks in sub-sections may not work

* **[Constructive heuristic](https://github.com/4342315yc/VRP-Algorithms/tree/master/Heuristic/Constructive)**
  * [Clarke and Wright savings algorithm](https://github.com/4342315yc/VRP-Algorithms/tree/master/Heuristic/Constructive/#clarke-and-wright-savings-algorithm)
  * [Matching Based](https://github.com/4342315yc/VRP-Algorithms/tree/master/Heuristic/Constructive/#matching-based)
  * [Multi-route Improvement Heuristic](https://github.com/4342315yc/VRP-Algorithms/tree/master/Heuristic/Constructive/#multi-route-improvement-heuristic)
    * [Thompson and Psaraftis](https://github.com/4342315yc/VRP-Algorithms/tree/master/Heuristic/Constructive/#thompson-and-psaraftic)
    * [Van Breedam](https://github.com/4342315yc/VRP-Algorithms/tree/master/Heuristic/Constructive/#van-breedam)
    * [Kinderwater and Savelsbergh](https://github.com/4342315yc/VRP-Algorithms/tree/master/Heuristic/Constructive/kinderwater-and-savesbergh)

* **[2-Phase heuristic](https://github.com/4342315yc/VRP-Algorithms/tree/master/Heuristic/2-Phase)**
  * [Cluster-First, Route-Second Algorithms](https://github.com/4342315yc/VRP-Algorithms/tree/master/Heuristic/2-Phase/#cluster-first-route-second-algorithms)
    * [Fisher and Jakimar](https://github.com/4342315yc/VRP-Algorithms/tree/master/Heuristic/2-Phase/#fisher-and-jakimar)
    * [The Petal Algorithm](https://github.com/4342315yc/VRP-Algorithms/tree/master/Heuristic/2-Phase/#the-petal-algorithm)
    * [The Sweep Algorithm](https://github.com/4342315yc/VRP-Algorithms/tree/master/Heuristic/2-Phase/#the-sweep-algorithm)
  * [Route-First, Cluster-Second Algorithms](https://github.com/4342315yc/VRP-Algorithms/tree/master/Heuristic/2-Phase/#route-first-cluster-second-algorithms)
    * [Beasley's Algorithm](https://github.com/4342315yc/VRP-Algorithms/tree/master/Heuristic/2-Phase/#beasleys-algorithm)

## Meta Heuristic Algorithms
* [Ant Algorithms](https://github.com/4342315yc/VRP-Algorithms/tree/master/Meta-Heuristic#ant-algorithms)
* [Constraint Programming](https://github.com/4342315yc/VRP-Algorithms/tree/master/Meta-Heuristic#constraint-programming)
* [Deterministic Annealing](https://github.com/4342315yc/VRP-Algorithms/tree/master/Meta-Heuristic#deterministic-annealing)
* [Genetic Algorithms](https://github.com/4342315yc/VRP-Algorithms/tree/master/Meta-Heuristic#genetic-algorithms)
* [Simulated Annealing](https://github.com/4342315yc/VRP-Algorithms/tree/master/Meta-Heuristic#simulated-annealing)
* [Tabu Search](https://github.com/4342315yc/VRP-Algorithms/tree/master/Meta-Heuristic#tabu-search)
  * [Granular Tabu](https://github.com/4342315yc/VRP-Algorithms/tree/master/Meta-Heuristic#granular-search)
  * [The Adaptive Memory Procedure](https://github.com/4342315yc/VRP-Algorithms/tree/master/Meta-Heuristic#the-adaptive-memory-procedure)
  * [Kelly and Xu](https://github.com/4342315yc/VRP-Algorithms/tree/master/Meta-Heuristic#kelly-and-xu)
  * [Taburoute](https://github.com/4342315yc/VRP-Algorithms/tree/master/Meta-Heuristic#taburoute)
  
