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

Proof

- Let's say we have two graphs, they are isomorphic, and we need to show that they do not need to be completely connected  
- We know that since the graphs are isomorphic, there is bijective function, f, that maps the two graphs, so that if two nodes are connected by an edge in the first graph, they must be mapped to two nodes connected by an edge in the second graph.  
- Any nodes that do not have edges are not restricted by the definition of our bijective function.
- In the case where we have some node in both graphs that do not have edges, the bijective function still applys, therefore two graphs do not have to be completely connected in order to be isomorphic.  

