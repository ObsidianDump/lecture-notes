A [[Binary Tree]] is an ordered [[Tree]] where each node can only carry a maximum of two children nodes. All children of a given node are labelled *left* and *right* with all operations favouring the the *left* most child before proceeding onto the right.
Some uses of [[Binary Tree]]'s include:
* Mathematic operations: being very useful in the ordering and structuring of given problems, breaking down a given instruction sets into branches to be solved fractally with the given parent being an operator.
```mermaid
graph TD;
id1((+)) --> id2((/));
id2((/)) --> id6((5));
id1((+)) --> id3(("-"));
id3(("-")) --> id8((4));
id3(("-")) --> id9((3));
id2((/)) --> id4((*));
id4((*)) --> id5((7));
id4((*)) --> id7((2));
```
* Coding Compilation: being able to do the above, turning complex human readable instructions into linear machine readable, machine code.

