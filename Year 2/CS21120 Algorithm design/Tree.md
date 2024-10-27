a [[Tree]] (T) is a set of nodes storing elements such that the nodes have a parent child relationship. If a given tree is non-empty it contains a root node, this is the parent to all other nodes in the tree.

```mermaid
graph TD;
id1((ROOT NODE)) --> id2((7));
id1((ROOT NODE)) --> id3((5));
id2((7)) --> id4((2));
id2((7)) --> id5((10));
id2((7)) --> id6((6));
id3((5)) --> id7((9));
id7((9)) --> id8((4));
id6((6)) --> id9((5));
id6((6)) --> id10((11));
```


