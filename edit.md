# Complexity

| Name           | Complexity         |
| -------------- | ------------------ |
| Selection sort | All case: $O(n^2)$ |
| Bubble Sort    | All case: $O(n^2)$      |
| Shell sort | **Worst**: $O(n^{3/2})$ |
| Early-termination Bubble sort | **Best:** $O(n)$<br />**Worst:** $O(n^2)$<br />**Avg:** $O(n^2)$ |
| Insertion sort | **Best:** $O(n)$<br />**Worst:** $O(n^2)$<br />**Avg:** $O(n^2)$ |
| Merge sort | All case: $O(nlogn)$ |
| Quick sort | **Best:** $O(nlogn)$<br />**Worst:** $O(n^2)$<br />**Avg**: $O(1.3999nlogn)$<br />Avg case 39% faster than `merge sort` |
| Heap sort | **Build + Deque**<br />$O(nlogn) + O(n) = O(nlogn)$ |
| DFS, BFS | **Adj Matrix:** $Θ(|V^2|)$<br />**Adj List**: $Θ(|V| + |E|)$ |
| Binary search | **Best**: $O(1)$<br />**Worst**: $O(log(n))$<br />If the array `is sorted` or has $O(1)$ access to any positon |
| BST Search | **Best**: $O(1)$<br />**Average:** $O(logn)$<br/>**Worst:** $O(n)$<br />If it’s a stick, that’s $h=n-1$ |
| Search in sorted list | **Merge sort + binary search**<br />$O(nlogn) + O(logn)  = O(nlogn)$<br />==Worth to presort when:==<br />$k >= \frac{nlogn}{n/2-logn}$ |
| AVL trees | **Height**: $h<= 1.4404log(n+2) - 1.3277$<br />**Search** and **Insert**: $O(logn)$<br />**Delete:** $O(logn)$<br />**Rebalance (rotations):** $O(logn)$<br />**Disadvantages**: Rotations are frequent and implementation is complex |
| 2-3 trees | **Height**: $log_3(n+1) -1 <= h <= log(n+1)-1$<br />**SEARCH, INSERT, DELETE**: $O(logn)$<br />**Rebalancing**: < $O(logn)$ |
| Heaps | **Height**: $h =  logn$<br />**Repair**: $O(logn)$<br />**C(n)** = $O(n)$<br />**Building:** $O(nlogn)$ |
| Distribution sorting | Worst case: $O(n)$ if $n > n_{max}$<br />Space: $O(n) + O(n_{max})$ |
| Hash tables | **List**<br />- Insert: $O(1)$<br />- Delete: $O(n)$<br />- Search: $O(n)$<br />**Balance Tree**<br />- Insert: $O(logn)$<br />- Delete: $O(logn)$<br />- Search: $O(logn)$<br />**Array**<br />- Insert: $O(logn)$<br />- Delete: $O(logn)$<br />- Search: $O(logn)$<br />**Open Hashing**<br />- Insert: $O(1)$<br />- Delete: propotional to list’s length<br />- Search: propotional to list’s length<br />- Average: $O(1)$ |
| Prim’s algorithm | **Min-heap** + **Adjacency list**<br />- $O(|E|log|V|)$<br />**Fibonacci heap + adjacency list**<br />- $O(|E| + |V|log|V|)$ |
| Kruskal’s algorithm | If there are edges:<br />- $O(|E|log|E|)$<br />If there is no edge:<br />- $O(|E| log |V|)$<br /> |
| Dijkstra’s Algorithm | Min-heap:<br />- $Θ(|E|log|V|)$ |
| Huffman’s Code | Min-heap:<br />- $Θ(nlogn)$<br />Sorted by probabilities:<br />- $Θ(n)$ |
| Edit distance | Worse and Average:<br />- Construction: $Θ(nm)$ where n and m is length of 2 strings.<br />- Backtrace complexity: $Θ(m+n)$ |
| Knapsnack problem | Build table: $Θ(nW)$<br />Backtrace complexity: $Θ(n+W)$ |
| Warshall’s algorithm | Complexity: $Θ(n^3)$<br />Space: $Θ(n^2)$<br />DFS & BFS: $Θ(n^2 + nm)$ for n, $Θ(n+m)$ for 1<br />If not many: $Θ(n^2)$ |

- **Stack**:
  - Add and remove at front.
    - [a] add b => [b,a]. remove b => [a]
- All `log`, `ln` has the same speed
- (n-1)! < n!
- When rotating for AVL trees. If one element changes its position to the right. We say R(that element). So draw first and then write rotation direction.

