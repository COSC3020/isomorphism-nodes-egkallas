[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/AtNXzL3S)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.<br>
A one-to-one function is a function where each element of the domain is paired with a unique element of the codomain. <br>
An onto function is a function where every element in the codomain has at least one corresponding element in the domain. <br>
In this context, these properties mean each node corresponds to another in each graph, and the edges are also preserved.
If one of the graphs doesn't have the same number of nodes, these properties don't hold because there would be an extra vertex in one graph without a corresponding vertex in the other.<br>
Therefor in order for a graph to be isomorphic, they must have the same number of nodes. 

