# CLRS 4th Edition → LeetCode Problem Mapping

A curated list of LeetCode problems aligned with each chapter. Focus on understanding the theory first, then reinforce with practice.

---

## Part I: Foundations

### Chapter 2: Getting Started

_Insertion sort, merge sort, algorithm analysis_

|Problem|Difficulty|Notes|
|---|---|---|
|[912. Sort an Array](https://leetcode.com/problems/sort-an-array/)|Medium|Implement merge sort|
|[147. Insertion Sort List](https://leetcode.com/problems/insertion-sort-list/)|Medium|Insertion sort on linked list|
|[88. Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/)|Easy|Merge step of merge sort|
|[21. Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/)|Easy|Merge concept|

### Chapter 4: Divide-and-Conquer

_Recurrences, master theorem, D&C algorithms_

| Problem                                                                                      | Difficulty | Notes                        |
| -------------------------------------------------------------------------------------------- | ---------- | ---------------------------- |
| [53. Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)                      | Medium     | Classic D&C (Kadane's is DP) |
| [169. Majority Element](https://leetcode.com/problems/majority-element/)                     | Easy       | Boyer-Moore or D&C           |
| [215. Kth Largest Element](https://leetcode.com/problems/kth-largest-element-in-an-array/)   | Medium     | Quickselect                  |
| [240. Search a 2D Matrix II](https://leetcode.com/problems/search-a-2d-matrix-ii/)           | Medium     | D&C approach                 |
| [23. Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/)              | Hard       | D&C merge                    |
| [4. Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | Hard       | Binary search D&C            |
| [932. Beautiful Array](https://leetcode.com/problems/beautiful-array/)                       | Medium     | D&C construction             |

---

## Part II: Sorting and Order Statistics

### Chapter 6: Heapsort

_Heaps, priority queues_

|Problem|Difficulty|Notes|
|---|---|---|
|[215. Kth Largest Element](https://leetcode.com/problems/kth-largest-element-in-an-array/)|Medium|Heap or quickselect|
|[347. Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)|Medium|Heap + hashmap|
|[295. Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/)|Hard|Two heaps|
|[703. Kth Largest Element in Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/)|Easy|Min heap of size k|
|[23. Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/)|Hard|Min heap approach|
|[973. K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/)|Medium|Max heap|
|[1046. Last Stone Weight](https://leetcode.com/problems/last-stone-weight/)|Easy|Max heap simulation|
|[621. Task Scheduler](https://leetcode.com/problems/task-scheduler/)|Medium|Greedy + heap|

### Chapter 7: Quicksort

_Partitioning, randomized quicksort_

|Problem|Difficulty|Notes|
|---|---|---|
|[912. Sort an Array](https://leetcode.com/problems/sort-an-array/)|Medium|Implement quicksort|
|[215. Kth Largest Element](https://leetcode.com/problems/kth-largest-element-in-an-array/)|Medium|Quickselect|
|[75. Sort Colors](https://leetcode.com/problems/sort-colors/)|Medium|Dutch National Flag partition|
|[283. Move Zeroes](https://leetcode.com/problems/move-zeroes/)|Easy|Partition variant|
|[905. Sort Array By Parity](https://leetcode.com/problems/sort-array-by-parity/)|Easy|Two-pointer partition|

### Chapter 8: Sorting in Linear Time

_Counting sort, radix sort, bucket sort_

|Problem|Difficulty|Notes|
|---|---|---|
|[274. H-Index](https://leetcode.com/problems/h-index/)|Medium|Counting sort|
|[347. Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)|Medium|Bucket sort approach|
|[451. Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency/)|Medium|Bucket sort|
|[164. Maximum Gap](https://leetcode.com/problems/maximum-gap/)|Medium|Bucket/radix sort|
|[561. Array Partition](https://leetcode.com/problems/array-partition/)|Easy|Counting sort applicable|

### Chapter 9: Medians and Order Statistics

_Selection algorithms, min/max_

|Problem|Difficulty|Notes|
|---|---|---|
|[215. Kth Largest Element](https://leetcode.com/problems/kth-largest-element-in-an-array/)|Medium|Quickselect (CLRS selection)|
|[4. Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/)|Hard|Binary search|
|[295. Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/)|Hard|Two heaps|
|[480. Sliding Window Median](https://leetcode.com/problems/sliding-window-median/)|Hard|Two heaps + removal|

---

## Part III: Data Structures

### Chapter 10: Elementary Data Structures

_Stacks, queues, linked lists_

|Problem|Difficulty|Notes|
|---|---|---|
|[20. Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)|Easy|Stack|
|[155. Min Stack](https://leetcode.com/problems/min-stack/)|Medium|Stack design|
|[232. Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/)|Easy|Two stacks|
|[225. Implement Stack using Queues](https://leetcode.com/problems/implement-stack-using-queues/)|Easy|Queue manipulation|
|[206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/)|Easy|Fundamental|
|[141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)|Easy|Floyd's algorithm|
|[21. Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/)|Easy|List manipulation|
|[146. LRU Cache](https://leetcode.com/problems/lru-cache/)|Medium|Doubly linked list + hashmap|
|[84. Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/)|Hard|Monotonic stack|
|[239. Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/)|Hard|Monotonic deque|

### Chapter 11: Hash Tables

_Chaining, open addressing, hash functions_

|Problem|Difficulty|Notes|
|---|---|---|
|[1. Two Sum](https://leetcode.com/problems/two-sum/)|Easy|Hash map lookup|
|[217. Contains Duplicate](https://leetcode.com/problems/contains-duplicate/)|Easy|Hash set|
|[242. Valid Anagram](https://leetcode.com/problems/valid-anagram/)|Easy|Character count map|
|[49. Group Anagrams](https://leetcode.com/problems/group-anagrams/)|Medium|Sorted string as key|
|[128. Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/)|Medium|Set + smart iteration|
|[560. Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/)|Medium|Prefix sum + hashmap|
|[146. LRU Cache](https://leetcode.com/problems/lru-cache/)|Medium|Hash + linked list|
|[380. Insert Delete GetRandom O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1/)|Medium|Hash + array|
|[706. Design HashMap](https://leetcode.com/problems/design-hashmap/)|Easy|Implement from scratch|

### Chapter 12: Binary Search Trees

_BST operations, traversals_

|Problem|Difficulty|Notes|
|---|---|---|
|[700. Search in a BST](https://leetcode.com/problems/search-in-a-binary-search-tree/)|Easy|Basic search|
|[701. Insert into a BST](https://leetcode.com/problems/insert-into-a-binary-search-tree/)|Medium|Insertion|
|[450. Delete Node in a BST](https://leetcode.com/problems/delete-node-in-a-bst/)|Medium|All 3 deletion cases|
|[98. Validate BST](https://leetcode.com/problems/validate-binary-search-tree/)|Medium|Inorder or bounds|
|[230. Kth Smallest Element in BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)|Medium|Inorder traversal|
|[108. Convert Sorted Array to BST](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)|Easy|Balanced construction|
|[235. LCA of BST](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/)|Medium|Use BST property|
|[173. BST Iterator](https://leetcode.com/problems/binary-search-tree-iterator/)|Medium|Controlled inorder|
|[96. Unique Binary Search Trees](https://leetcode.com/problems/unique-binary-search-trees/)|Medium|Catalan numbers|

### Chapter 13: Red-Black Trees

_Balanced BSTs (concepts transfer to any balanced tree)_

|Problem|Difficulty|Notes|
|---|---|---|
|[110. Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/)|Easy|Check balance property|
|[1382. Balance a BST](https://leetcode.com/problems/balance-a-binary-search-tree/)|Medium|Rebuild balanced|
|[315. Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/)|Hard|BST/BIT/merge sort|

_Note: LeetCode rarely tests RB-tree implementation directly. Understanding helps with TreeMap/TreeSet usage._

---

## Part IV: Advanced Design and Analysis Techniques

### Chapter 14: Dynamic Programming

_Optimal substructure, overlapping subproblems, memoization_

**1D DP**

|Problem|Difficulty|Notes|
|---|---|---|
|[70. Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)|Easy|Fibonacci variant|
|[198. House Robber](https://leetcode.com/problems/house-robber/)|Medium|Classic 1D|
|[213. House Robber II](https://leetcode.com/problems/house-robber-ii/)|Medium|Circular array|
|[139. Word Break](https://leetcode.com/problems/word-break/)|Medium|String DP|
|[322. Coin Change](https://leetcode.com/problems/coin-change/)|Medium|Unbounded knapsack|
|[300. Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)|Medium|Classic LIS|
|[152. Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/)|Medium|Track min and max|

**2D DP**

|Problem|Difficulty|Notes|
|---|---|---|
|[62. Unique Paths](https://leetcode.com/problems/unique-paths/)|Medium|Grid DP|
|[64. Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/)|Medium|Grid DP|
|[1143. Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/)|Medium|CLRS example|
|[72. Edit Distance](https://leetcode.com/problems/edit-distance/)|Medium|Classic string DP|
|[416. Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)|Medium|0/1 Knapsack|
|[494. Target Sum](https://leetcode.com/problems/target-sum/)|Medium|Subset sum variant|
|[518. Coin Change II](https://leetcode.com/problems/coin-change-ii/)|Medium|Count combinations|
|[97. Interleaving String](https://leetcode.com/problems/interleaving-string/)|Medium|Two-string DP|

**Interval DP**

|Problem|Difficulty|Notes|
|---|---|---|
|[516. Longest Palindromic Subsequence](https://leetcode.com/problems/longest-palindromic-subsequence/)|Medium|Interval DP|
|[1039. Minimum Score Triangulation](https://leetcode.com/problems/minimum-score-triangulation-of-polygon/)|Medium|Matrix chain multiplication variant|
|[312. Burst Balloons](https://leetcode.com/problems/burst-balloons/)|Hard|MCM pattern|
|[87. Scramble String](https://leetcode.com/problems/scramble-string/)|Hard|3D DP|

**Advanced DP**

|Problem|Difficulty|Notes|
|---|---|---|
|[10. Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/)|Hard|String matching DP|
|[44. Wildcard Matching](https://leetcode.com/problems/wildcard-matching/)|Hard|Simpler regex|
|[115. Distinct Subsequences](https://leetcode.com/problems/distinct-subsequences/)|Hard|Counting DP|
|[123. Best Time to Buy and Sell Stock III](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/)|Hard|State machine DP|
|[188. Best Time to Buy and Sell Stock IV](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iv/)|Hard|Generalized|

### Chapter 15: Greedy Algorithms

_Greedy choice property, activity selection_

|Problem|Difficulty|Notes|
|---|---|---|
|[455. Assign Cookies](https://leetcode.com/problems/assign-cookies/)|Easy|Simple greedy|
|[435. Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/)|Medium|Activity selection!|
|[452. Minimum Arrows to Burst Balloons](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/)|Medium|Interval greedy|
|[55. Jump Game](https://leetcode.com/problems/jump-game/)|Medium|Greedy reachability|
|[45. Jump Game II](https://leetcode.com/problems/jump-game-ii/)|Medium|Min jumps|
|[134. Gas Station](https://leetcode.com/problems/gas-station/)|Medium|Circular greedy|
|[763. Partition Labels](https://leetcode.com/problems/partition-labels/)|Medium|Last occurrence greedy|
|[621. Task Scheduler](https://leetcode.com/problems/task-scheduler/)|Medium|Greedy scheduling|
|[135. Candy](https://leetcode.com/problems/candy/)|Hard|Two-pass greedy|
|[330. Patching Array](https://leetcode.com/problems/patching-array/)|Hard|Greedy coverage|

**Huffman Coding Related**

|Problem|Difficulty|Notes|
|---|---|---|
|[1167. Minimum Cost to Connect Sticks](https://leetcode.com/problems/minimum-cost-to-connect-sticks/)|Medium|Huffman-like|

---

## Part V: Advanced Data Structures

### Chapter 17: Augmenting Data Structures

_Order statistics trees, interval trees_

|Problem|Difficulty|Notes|
|---|---|---|
|[315. Count of Smaller Numbers After Self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/)|Hard|Augmented BST / BIT|
|[493. Reverse Pairs](https://leetcode.com/problems/reverse-pairs/)|Hard|Merge sort / BIT|
|[327. Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/)|Hard|Merge sort / BIT|
|[56. Merge Intervals](https://leetcode.com/problems/merge-intervals/)|Medium|Interval concepts|
|[57. Insert Interval](https://leetcode.com/problems/insert-interval/)|Medium|Interval insertion|
|[986. Interval List Intersections](https://leetcode.com/problems/interval-list-intersections/)|Medium|Two pointers on intervals|

### Chapter 19: Data Structures for Disjoint Sets

_Union-Find_

|Problem|Difficulty|Notes|
|---|---|---|
|[200. Number of Islands](https://leetcode.com/problems/number-of-islands/)|Medium|Union-Find or DFS|
|[547. Number of Provinces](https://leetcode.com/problems/number-of-provinces/)|Medium|Classic Union-Find|
|[684. Redundant Connection](https://leetcode.com/problems/redundant-connection/)|Medium|Cycle detection|
|[721. Accounts Merge](https://leetcode.com/problems/accounts-merge/)|Medium|Union-Find application|
|[128. Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/)|Medium|Union-Find or set|
|[1319. Number of Operations to Make Network Connected](https://leetcode.com/problems/number-of-operations-to-make-network-connected/)|Medium|Connected components|
|[399. Evaluate Division](https://leetcode.com/problems/evaluate-division/)|Medium|Weighted Union-Find|
|[765. Couples Holding Hands](https://leetcode.com/problems/couples-holding-hands/)|Hard|Union-Find cycles|
|[839. Similar String Groups](https://leetcode.com/problems/similar-string-groups/)|Hard|Group by similarity|

---

## Part VI: Graph Algorithms

### Chapter 20: Elementary Graph Algorithms

_BFS, DFS, topological sort, strongly connected components_

**BFS Problems**

|Problem|Difficulty|Notes|
|---|---|---|
|[733. Flood Fill](https://leetcode.com/problems/flood-fill/)|Easy|BFS/DFS intro|
|[994. Rotting Oranges](https://leetcode.com/problems/rotting-oranges/)|Medium|Multi-source BFS|
|[286. Walls and Gates](https://leetcode.com/problems/walls-and-gates/)|Medium|Multi-source BFS|
|[127. Word Ladder](https://leetcode.com/problems/word-ladder/)|Hard|BFS shortest path|
|[126. Word Ladder II](https://leetcode.com/problems/word-ladder-ii/)|Hard|BFS + backtracking|
|[1091. Shortest Path in Binary Matrix](https://leetcode.com/problems/shortest-path-in-binary-matrix/)|Medium|8-directional BFS|
|[752. Open the Lock](https://leetcode.com/problems/open-the-lock/)|Medium|State-space BFS|
|[815. Bus Routes](https://leetcode.com/problems/bus-routes/)|Hard|Graph modeling + BFS|

**DFS Problems**

|Problem|Difficulty|Notes|
|---|---|---|
|[200. Number of Islands](https://leetcode.com/problems/number-of-islands/)|Medium|Classic DFS|
|[695. Max Area of Island](https://leetcode.com/problems/max-area-of-island/)|Medium|DFS with counting|
|[417. Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/)|Medium|Multi-source DFS|
|[130. Surrounded Regions](https://leetcode.com/problems/surrounded-regions/)|Medium|Border DFS|
|[79. Word Search](https://leetcode.com/problems/word-search/)|Medium|DFS backtracking|
|[329. Longest Increasing Path in Matrix](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/)|Hard|DFS + memoization|
|[547. Number of Provinces](https://leetcode.com/problems/number-of-provinces/)|Medium|Connected components|
|[841. Keys and Rooms](https://leetcode.com/problems/keys-and-rooms/)|Medium|Graph traversal|

**Topological Sort**

|Problem|Difficulty|Notes|
|---|---|---|
|[207. Course Schedule](https://leetcode.com/problems/course-schedule/)|Medium|Cycle detection|
|[210. Course Schedule II](https://leetcode.com/problems/course-schedule-ii/)|Medium|Return topo order|
|[269. Alien Dictionary](https://leetcode.com/problems/alien-dictionary/)|Hard|Build graph + topo sort|
|[310. Minimum Height Trees](https://leetcode.com/problems/minimum-height-trees/)|Medium|Topo sort from leaves|
|[802. Find Eventual Safe States](https://leetcode.com/problems/find-eventual-safe-states/)|Medium|Reverse topo sort|
|[1136. Parallel Courses](https://leetcode.com/problems/parallel-courses/)|Medium|Topo sort levels|
|[2115. Find All Possible Recipes](https://leetcode.com/problems/find-all-possible-recipes-from-given-supplies/)|Medium|Topo sort application|

**Strongly Connected Components**

|Problem|Difficulty|Notes|
|---|---|---|
|[1192. Critical Connections in Network](https://leetcode.com/problems/critical-connections-in-a-network/)|Hard|Tarjan's bridges|
|[802. Find Eventual Safe States](https://leetcode.com/problems/find-eventual-safe-states/)|Medium|SCC concepts|
|[2360. Longest Cycle in Graph](https://leetcode.com/problems/longest-cycle-in-a-graph/)|Hard|Cycle detection|

### Chapter 21: Minimum Spanning Trees

_Kruskal's, Prim's algorithms_

|Problem|Difficulty|Notes|
|---|---|---|
|[1584. Min Cost to Connect All Points](https://leetcode.com/problems/min-cost-to-connect-all-points/)|Medium|Classic MST|
|[1135. Connecting Cities With Minimum Cost](https://leetcode.com/problems/connecting-cities-with-minimum-cost/)|Medium|Direct Kruskal/Prim|
|[1168. Optimize Water Distribution](https://leetcode.com/problems/optimize-water-distribution-in-a-village/)|Hard|MST with virtual node|
|[1489. Find Critical and Pseudo-Critical Edges](https://leetcode.com/problems/find-critical-and-pseudo-critical-edges-in-mst/)|Hard|MST edge analysis|
|[1579. Remove Max Number of Edges](https://leetcode.com/problems/remove-max-number-of-edges-to-keep-graph-fully-traversable/)|Hard|Two MSTs|
|[1631. Path With Minimum Effort](https://leetcode.com/problems/path-with-minimum-effort/)|Medium|MST/Binary search + BFS|
|[778. Swim in Rising Water](https://leetcode.com/problems/swim-in-rising-water/)|Hard|MST variant|

### Chapter 22: Single-Source Shortest Paths

_Bellman-Ford, Dijkstra's, DAG shortest paths_

**Dijkstra's Algorithm**

|Problem|Difficulty|Notes|
|---|---|---|
|[743. Network Delay Time](https://leetcode.com/problems/network-delay-time/)|Medium|Classic Dijkstra|
|[787. Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/)|Medium|Modified Dijkstra/BFS|
|[1514. Path with Maximum Probability](https://leetcode.com/problems/path-with-maximum-probability/)|Medium|Max-product Dijkstra|
|[505. The Maze II](https://leetcode.com/problems/the-maze-ii/)|Medium|Dijkstra on grid|
|[1631. Path With Minimum Effort](https://leetcode.com/problems/path-with-minimum-effort/)|Medium|Dijkstra variant|
|[778. Swim in Rising Water](https://leetcode.com/problems/swim-in-rising-water/)|Hard|Dijkstra/binary search|
|[1368. Minimum Cost to Make Valid Path](https://leetcode.com/problems/minimum-cost-to-make-at-least-one-valid-path-in-a-grid/)|Hard|0-1 BFS / Dijkstra|
|[882. Reachable Nodes in Subdivided Graph](https://leetcode.com/problems/reachable-nodes-in-subdivided-graph/)|Hard|Dijkstra application|

**Bellman-Ford / Negative Weights**

|Problem|Difficulty|Notes|
|---|---|---|
|[787. Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/)|Medium|Bellman-Ford with K iterations|
|[1865. Finding Pairs With Certain Sum](https://leetcode.com/problems/finding-pairs-with-a-certain-sum/)|Medium|Relaxation concept|

**0-1 BFS (Special case)**

|Problem|Difficulty|Notes|
|---|---|---|
|[1368. Minimum Cost to Make Valid Path](https://leetcode.com/problems/minimum-cost-to-make-at-least-one-valid-path-in-a-grid/)|Hard|0-1 BFS|
|[2290. Minimum Obstacle Removal](https://leetcode.com/problems/minimum-obstacle-removal-to-reach-corner/)|Hard|0-1 BFS|

### Chapter 23: All-Pairs Shortest Paths

_Floyd-Warshall, Johnson's algorithm_

|Problem|Difficulty|Notes|
|---|---|---|
|[1334. Find the City With Fewest Neighbors](https://leetcode.com/problems/find-the-city-with-the-smallest-number-of-neighbors-at-a-threshold-distance/)|Medium|Floyd-Warshall|
|[399. Evaluate Division](https://leetcode.com/problems/evaluate-division/)|Medium|Floyd-Warshall / Union-Find|
|[1462. Course Schedule IV](https://leetcode.com/problems/course-schedule-iv/)|Medium|Transitive closure|
|[847. Shortest Path Visiting All Nodes](https://leetcode.com/problems/shortest-path-visiting-all-nodes/)|Hard|BFS + bitmask|
|[1617. Count Subtrees With Max Distance](https://leetcode.com/problems/count-subtrees-with-max-distance-between-cities/)|Hard|Floyd-Warshall + bitmask|

### Chapter 24: Maximum Flow

_Ford-Fulkerson, Edmonds-Karp_

|Problem|Difficulty|Notes|
|---|---|---|
|[785. Is Graph Bipartite?](https://leetcode.com/problems/is-graph-bipartite/)|Medium|Bipartite check (flow prereq)|
|[886. Possible Bipartition](https://leetcode.com/problems/possible-bipartition/)|Medium|Bipartite coloring|
|[1349. Maximum Students Taking Exam](https://leetcode.com/problems/maximum-students-taking-exam/)|Hard|Max flow / Hungarian|
|[1066. Campus Bikes II](https://leetcode.com/problems/campus-bikes-ii/)|Medium|Assignment problem|
|[LCP 04. Domino Covering](https://leetcode.cn/problems/broken-board-dominoes/)|Hard|Max matching|

_Note: Pure max-flow problems are rare on LeetCode. Focus on bipartite matching concepts._

### Chapter 25: Matchings in Bipartite Graphs

_Hungarian algorithm, Hopcroft-Karp_

|Problem|Difficulty|Notes|
|---|---|---|
|[785. Is Graph Bipartite?](https://leetcode.com/problems/is-graph-bipartite/)|Medium|Foundation|
|[886. Possible Bipartition](https://leetcode.com/problems/possible-bipartition/)|Medium|2-coloring|
|[1349. Maximum Students Taking Exam](https://leetcode.com/problems/maximum-students-taking-exam/)|Hard|Bipartite matching|
|[1820. Maximum Number of Accepted Invitations](https://leetcode.com/problems/maximum-number-of-accepted-invitations/)|Medium|Hungarian algorithm|
|[1947. Maximum Compatibility Score Sum](https://leetcode.com/problems/maximum-compatibility-score-sum/)|Medium|Assignment problem|

---

## Bonus: Graph Patterns Cheat Sheet

|Pattern|When to Use|Key Problems|
|---|---|---|
|**BFS**|Shortest path (unweighted), level-order|994, 127, 752|
|**DFS**|Connectivity, cycles, backtracking|200, 79, 329|
|**Topo Sort**|Dependencies, ordering|207, 210, 269|
|**Dijkstra**|Shortest path (weighted, non-negative)|743, 1514|
|**Bellman-Ford**|Negative weights, K edges limit|787|
|**Floyd-Warshall**|All pairs, small graphs|1334, 399|
|**Union-Find**|Connectivity, MST (Kruskal)|200, 547, 1584|
|**MST**|Min cost to connect all|1584, 1135|
|**Bipartite**|Two-group problems, matching|785, 886|

---

## Study Strategy

### Per Chapter Workflow

1. **Read CLRS chapter** — understand the theory
2. **Do 2-3 Easy/Medium problems** — apply concepts
3. **Attempt 1 Hard problem** — stretch understanding
4. **Review and tag** — connect theory to practice

---
