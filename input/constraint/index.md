```mermaid
---
title: Constraint
---
classDiagram
  direction LR
  Constraint <|-- CastConstraint
  Constraint <|-- GlobalVehicleBreaksConstraint
  Constraint <|-- DifferentFromValues
  Constraint <|-- TypeRegulationsConstraint
  DifferentFromValues --> RoutingModelVisitor
```
