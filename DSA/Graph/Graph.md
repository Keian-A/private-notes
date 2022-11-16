# What is a Graph?

A graph is a data structure which contains a set of nodes, or vertices - connected to eachother through a set of edges.

Graphs are similar to trees, but different in the connections.

Notes from [video](https://www.youtube.com/watch?v=gXgEDyodOJU):

Graph: A graph **G** is an *ordered pair* of a set **V** of vertices and a set **E** of edges.

G = (V,E)

###### This is an **ordered pair** which means that order **does matter** when referring to the pair. This can be determined with parenthesis vs curly braces when written out.

###### Ordered pair:
###### - (a, b) != (b, a) if a != b

###### Unordered pair:
###### - {a, b} == {b, a}

A graphs vertices can be represented as:
- V = {v1, v2, v3, v4, v5, v6}

Edges are represented based on the *type* of edges the graph contains. You can have multiple edge types:

- Directed: Where v1 has an edge pointed to v2, but not the other way around. (u, v)
- Undirected: Where the connection between v1 and v2 is both ways.

In a directed edge, you draw them with an arrow head pointing from the origin vertex to the destination vertex.

![Edge types](../../Images/Edges.png)

So, edges in a fully undirected graph can be represented as:

- E = { {v1, v2}, {v1, v3}, {v1, v4}, etc...}

If a graph is fully directed, it is called a "Directed graph" or a "Digraph."

[<-- DSA Table of Contents](../DSATOC.md)