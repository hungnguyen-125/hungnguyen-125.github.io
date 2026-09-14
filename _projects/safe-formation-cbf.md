---
layout: page
title: Safe Formation Control with CBFs
description: Distributed multi-robot formation control with RDCBF- and HOCBF-based QP safety filters.
importance: 2
category: control
related_publications: false
---

This semester project studies **safety-critical formation control for multi-robot systems**.

- Implemented a **distributed consensus-based formation controller** for double-integrator agents using local neighbor information.
- Implemented two independent **CBF-QP safety filters**: Relaxed Distributed CBF (RDCBF) and High-Order CBF (HOCBF).
- Validated the framework in collision-prone simulations including **19-agent position swapping** and **6-drone formation** under disturbances.

The safety layer minimally modifies the nominal formation-control input while enforcing inter-agent and obstacle collision-avoidance constraints.
