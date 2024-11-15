---
title: Graph
date: 2024-08-03
tags:
  - Permanent
refs:
  - "[[Data Structures]]"
netlinks: 
bookref:
  - "[[Grokking Algorithms|Grokking Algorithms]]"
---
# Graph

# Graph
```ad-info
title: Structure of a graph
Graphs are made up of nodes and edges. A node can be directly connected to many other nodes. Those nodes are called its neighbors.

![[Pasted image 20240803173257.png]]
```

```ad-note
title: Modelling connections using graph
Graphs are a way to model how different things are connected to one another.

![[Pasted image 20240803173226.png]]
```

```ad-note
To search elements in a graph we need to use Breadth-first search.
[[Permanent/Breadth-first search]]
```

## Implementation
```python
from typing import Dict, List

class Graph:
    def __init__(self, data: Dict[str, List[str]]):
        self.graph = data

    def __repr__(self) -> str:
        return str(self.graph)

    def __str__(self) -> str:
        return f"{self.graph}"

    def __getitem__(self, key: str) -> List[str]:
        return self.graph[key]

```
This graph:
![[Pasted image 20240803214754.png]]
Represented in python
```python
graph = Graph(
    {
        "you": ["alice", "bob", "claire"],
        "bob": ["anuj", "peggy"],
        "alice": ["peggy"],
        "anuj": [],
        "claire": ["thom", "jonny"],
        "peggy": [],
        "thom": [],
        "jonny": [],
    }
)
```

## Types of graph

1. Undirected Graph
2. Directed Graph
![[Pasted image 20240803220642.png]]

---

## References
