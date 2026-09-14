---
layout: page
title: Humanoid Locomotion Control
description: Rigid-body MPC tuning and gait-transition research on the Motion1 humanoid robot.
importance: 1
category: robotics
related_publications: false
---

During a two-month controls internship at **VinMotion**, I worked on model-based humanoid locomotion control for the Motion1 platform.

### MPC tuning on hardware

I tuned **stance–swing contact constraints** and **QP weighting matrices** in a rigid-body MPC framework. This work contributed to hardware experiments including **stair climbing** and fast walking at speeds up to **0.6 m/s**.

### Gait-transition strategy

I also investigated a contact-schedule-based gait-transition strategy for an **NMPC locomotion planner**. Instead of switching only between simple stance and swing states using a basic finite-state machine, the approach represents locomotion as sequences of contact modes including **stance, swing, and flight phases**, with the goal of producing smoother transitions as commanded speed changes.

> This page only summarizes non-confidential technical work. No proprietary source code or internal materials are published here.
