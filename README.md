[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/AtNXzL3S)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Answer
We say that two graphs are isomorphic if and only if they are onto and one-to-one. The graph must be onto so each node in G1 must link to a node in G2. The graph is also one-to-one so each node in G1 must map to only one node of G2. If G1 has more nodes than G2 then there will always be a node in G1 that isnt mapped to a unique node in G2 invalidating the one-to-one property. This also doesnt work as if we go the other ways from G2 to G1 there are not enough nodes to respect the onto and one-to-one preperty. So yes if two graphs have different number of nodes they cannot be isomorphic.