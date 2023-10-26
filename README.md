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

- We have two graphs $A=(V_1 , E_1)$ and $B=(V_2 , E_2)$ that are isomorphic to eachother and to themselves (i.e. they are both one to one and onto). There exists a disconnected node in $A$ therefore $A$ is not completley connected. If there is a disconnected node in $A$ such that $(u,v) \notin E_1$ and there is a one to one and onto relation between $A$ and $B$ then there must also be a disconnected node in $B$ such that (f(u),f(v)) \notin E_2$. Since $A$ and $B$ are isomorphic and there is a one to one and onto mapping even when $A$ and $B$ are not completley connected graphs, then if two graphs $A$ and $B$ are isomorphic they do not have to be completely connected.

