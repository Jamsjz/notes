---
title:Breadth-first search
date: 2024-08-03
tags:
  - Permanent
refs: 
  - "[[Algorithms]]"
netlinks:
bookrefs:
  - "[[Books/Grokking Algorithms|Grokking Algorithms]]"
---
# Breadth-first search

```ad-important
Breadth-first search not only finds a path from A to B, it also finds the shortest path.
```

```ad-abstract
title: Steps:
1. You see your nearest neighbours.
2. You ask if any of those neighbours is the item you are searching.
3. You repeat same steps for those neighbours(put those neighbours as starting point now) until you find the item.
```

```ad-info
- You have to check every neighbour of yours and your neigbours' and so on.
- The algorithm will not stop till:
	1. All entities in the network are checked
	2. The item is found.
```

## Shortest Path Problem

![[Pasted image 20240803184230.png]]

```ad-todo
title: Goal
You want to go from Twin Peaks to the Golden Gate Bridge.
```


```ad-example
Here,
1. first see the map
2. There are 2 neighbours from twin peaks.
3. None of those are golden gate bridge.
4. Now check for the neighbour of your 2 neighbours.
5. The next stop is not destination either.
6. DO this process again.
7. Disregard anything you have already visited(check duplication-> [[Literature/Hash Tables|Hash Tables]])
8. Keep on checking, finaaly you reach golden bridge.
![[Pasted image 20240803185053.png]]
```

## Implementation

```python
from typing import Dict, List, Set, TypeVar, Union
from collections import deque


class Graph:
    def __init__(self, data: Dict[str, List[str]]):
        self.graph = data

    def __repr__(self) -> str:
        return str(self.graph)

    def __str__(self) -> str:
        return f"{self.graph}"

    def __getitem__(self, key: str) -> List[str]:
        return self.graph[key]

    T = TypeVar("T")

    def search(self, start_point: T, end_points: Union[Set[T], T]):
        assert all(var is not None for var in [start_point, end_points])

        search_queue = deque([(start_point, [start_point])])
        visited = set()
        while search_queue:
            current, path = search_queue.popleft()

            if current in end_points:
                return path

            if current in visited:
                continue

            visited.add(current)
            neighbors = self.graph[current]
            for neighbor in neighbors:
                if neighbor not in visited:
                    search_queue.append((neighbor, path + [neighbor]))

        return None


graph = Graph(
    {
        1: [2, 3, 4, 5],
        2: [6, 7, 8],
        3: [9, 10, 11],
        4: [12, 13, 14],
        5: [15, 16, 17],
        6: [22],
        7: [18],
        8: [18],
        9: [8],
        10: [19],
        11: [19],
        12: [11, 20],
        13: [20],
        14: [21],
        15: [14],
        16: [],
        17: [],
        18: [],
        19: [22],
        20: [22],
        21: [22],
        22: [],
    }
)

print(graph.search(1, {22}))

```



---

## References
