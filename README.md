# Floyd-Warshall-Algorithm-
Floyd Warshall Algorithm implemented in C language for finding shortest path between all nodes in a graph represented in Matrix form

Input Format

The first line contains an integer, , denoting the number of queries. The subsequent lines describe each query in the following format:

The first line contains two space-separated integers describing the respective values of  (the number of nodes) and  (the number of edges) in the graph.
Each line  of the  subsequent lines contains two space-separated integers,  and , describing an edge connecting node  to node .
The last line contains a single integer, , denoting the index of the starting node.





Output Format

For each of the q  queries, print a single line of n-1  space-separated integers denoting the shortest distances to each of the n-1  other nodes from starting position . These distances should be listed sequentially by node number (i.e.1,2,....n ), but should not include node s. If some node is unreachable from s, print  -1 as the distance to that node.



Sample Input

2
4 2
1 2
1 3
1
3 1
2 3
2





Sample Output

6 6 -1
-1 6
