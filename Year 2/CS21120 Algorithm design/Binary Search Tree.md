A [[Binary Search Tree]] is a [[Binary Tree]] used to store information, each terminal node in a [[Binary Search Tree]] contain a [[Key-value pair]] (*k, v*) with the keys stored on the left of the subtree being less then *k* and the ones on the right being greater.
```mermaid

erDiagram

ROOT-NODE ||--|| NODE-1 : left
ROOT-NODE ||--|| NODE-2 : right
ROOT-NODE { 
parent NULL 
left NODE-1
right NODE-2
key TWO
element Bristol
}

NODE-1 ||--|| NODE-5 : left
NODE-1 { 
parent ROOT-NODE
left NODE-1
right NODE-2
element Chicargo
}

NODE-2 ||--|| NODE-3 : left
NODE-2 ||--|| NODE-4 : right
NODE-2 { 
parent ROOT-NODE
left NODE-3
right NODE-4
element Tokyo
}

NODE-3 { 
parent NODE-2
left NODE-1
right NODE-2
element London
}

NODE-4 { 
parent NODE-2
left NODE-1
right NODE-2
element Cinderford
}

NODE-5 { 
parent ROOT-NODE
left NODE-1
right NODE-2
element Liverpool
}
```
```mermaid
graph TD
id1((44)) --> id2((22))
id1((44)) --> id3((100))
id2((22))
```

