---
id: vatakntmpixw8trhk0j7d18
title: Q1. How many people here have released a OSHW project? (x1/y)
desc: ''
updated: 1732313102673
created: 1727901744843
---

## example projects
- led prototype board light-on wsd 20 clone stm32 - up and running
- halloween vending machine
  build earrings for rabbi
- rc2014

## notes

- diffs are useless unless you pay for a service
- openscad - jump to microelectronics
- challenge getting into digital space
- "structural diffing" - see diff tastic
- need for name-spacing; unambiguous means of referencing component instances
  - need a means of mapping dof schema to other tools (e.g., KiCad, FreeCAD)
    - this enables referencing data (s.a., part description) in DOF to enhance understanding data in other tools (e.g., what is the purpose of capacitor C2 in board layout)
    - this enables deeper referencing within instructions (e.g., where to place capacitor on a board based on board layout within assembly instructions)
  - any instance of a component in DOF needs to have a (fully qualified?) singular definitive name; this should be one-to-one and onto
    - investigate connection between structural diffing and mapping to other tools in user stories
- need context as to why a design was changed (e.g., a capacitor was swapped out or removed), or any design decision
