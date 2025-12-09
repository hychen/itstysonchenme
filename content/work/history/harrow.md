---
title: "Harrow"
date: 2013-05-04
---

Harrow was an experimental implementation of Arrows as executable pipelines in Python, inspired by the Arrow abstraction in functional programming.

The project treated execution not as isolated function calls, but as composable structures supporting forward and backward composition, branching, fan-in/fan-out, parallel execution, and looping. Execution order was expressed through formal combinators rather than implicit control flow.

By modeling execution pipelines as Arrow compositions, Harrow made execution order itself a first-class, manipulable object. State propagation, feedback, and trace-like behaviors were represented structurally within the execution model.

This work predates any semantic or ontological framing. It is documented here as an early formal exploration of execution order as a compositional and transformable structure—an important prerequisite for later work on executable semantic order, but not yet a semantic system itself.

- [github](https://github.com/hychen/harrow)
