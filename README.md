# Topological_sorting_tarjan
The Tarjan algorithm based Topological sorting algorithm. 
Only use Numpy. 

 Parameter
    -----
    g: the adjacency matrix of a graph, store as a two-dim n*n numpy.array.
    The first dim means the source and the second dim means the target.
    Example, `g[1][2] = 1` means the connection from 1 to 2 is exist.

    Notes
    -----
    The property of nodes are store in the one-dim numpy.array.
    Example, `discovery[1] = 12` means the discovery time of 1 is 12.


    See also
    --------
    [1]. Introduction to algorithms[M]. MIT press, 2009.
    [2]. Tarjan, RE, Depth-first search and linear graph algorithms,
         SIAM Journal on Computing, 1972, 1 (2): 146–160, doi:10.1137/0201010
    """
