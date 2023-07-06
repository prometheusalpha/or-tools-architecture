---
title: Input
---
```mermaid
classDiagram
  direction LR
  RoutingModel --> Dimension
  Dimension --> TransitCallback
  RoutingModel --> Solver
  Solver --> Constraint
  Constraint --> IntExpr
  RoutingModel --> DisjunctionIndex
  RoutingModel --> RoutingSearchParameters
```
