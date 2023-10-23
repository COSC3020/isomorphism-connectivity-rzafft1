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

- lets assume we have two graphs, $G_1=(V_1 , E_1)$ and $G_2=(V_2 , E_2)$. $G_1$ and $G_2$ are isomorphic such that there exists a function $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

- if the two graphs are isomorphic and they have the same number of nodes and edges, then ...

- $(\forall v \in V) \sum_{v \in V_1} deg(v) \implies \sum_{f(v) \in V_2} deg(f(v))$

- $\sum_{v \in V_1} deg(v) \implies \sum_{f(v) \in V_2} deg(f(v)) $

- $(deg(v) = deg(f(v))) \implies  2(E_1) = 2(E_2)$

- now lets assume $G_1$ is not completley connected such that $(u, v) \notin E_1$.

- $(u,v) \notin E1 \implies (f(u),f(v)) \notin E_2$ (i.e. we show that if $G_1$ is not completley connected, then $G_2$ must also not be completley connected)

- this shows that if $G_1$ and $G_2$ are isomorphic, there can exist a disconnected node in $G_1$ as long as there also exists a corresponding disconnected node in $G_2$ such that $(u,v) \notin E1 \implies (f(u),f(v)) \notin E_2$ (i.e. $G_1$ and $G_2$ do not have to be completley connected in order be isomorphic)

