---
title: Routing model
---

```mermaid
classDiagram
    RoutingModel --> Solver
    RoutingModel --> RoutingIndexManager
    RoutingModel --> RoutingSearchParameters
    RoutingModel --> RoutingDimension
    RoutingDimension --> SimpleBoundCosts
```
