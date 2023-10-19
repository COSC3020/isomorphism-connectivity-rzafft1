[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12380726&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do \emph{not} have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.


$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

**Three Required Properties for an Isomorphism**
- Both graphs $G_1$ and $G_2$ have the same number of vertices
- Both graphs $G_1$ and $G_2$ have the same number of edges
- Every edge in graphs $G_1$ and $G_2$ have the same degree

Proof

- $\text{we have a graph, } G_1=(V_1 , E_1)$ 

- $G_1 \text{ has a disconnected node such that } (u, v) \notin E_1$ 

- we need to show that that there exists two nodes in $G_1$ that are not connected by an edge

- $(u,v) \notin E1 \implies (f(u),f(v)) \notin E_2$ (i.e. we show that if we have a disconnected node in $G_1$, there also must be a disconnected node in $G_2$)

- prove that degrees are the same for both graphs... NOTE : if $ G = (V,E) \text{ then } \sum_{v \in V} deg(v) = 2|E|$

- $\sum_{v \in V_1} deg(v) \implies \sum_{f(v) \in V_2} deg(f(v)) $

- $(deg(v) = deg(f(v))) \implies  2(E_1) = 2(E_2)$

- $(E_1) \implies (E_2)$ This shows that all three properties of an isomorphism are still held (i.e. both graphs have the same number of nodes, same number of edges, and every edge in the two graphs have the same degree)

- therefore, the the graphs do not need to be completley connected in order to be isomorphic,

