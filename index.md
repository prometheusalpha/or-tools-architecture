---
title: Routing model
---
```mermaid
classDiagram
    class RoutingModel {
    }
    RoutingModel --> Solver
    RoutingModel --> RoutingIndexManager
    RoutingModel --> RoutingSearchParameters
    RoutingModel --> RoutingDimension
    RoutingDimension --> SimpleBoundCosts
```
