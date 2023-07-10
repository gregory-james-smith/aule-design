---
title: Specification
---

# Overview

The design language should follow the [M3 material design specification](https://m3.material.io/) with the following exceptions.

# Chips

Use square chips from M2.

| M3 | Description |
|-|-|
| input |  | 
| filter | Known as "choice" chips in M2. |
| assist | A specialisation of "action" chips from M2. |
| suggestion | A specialisation of "action" chips from M2. |

## Input chips

Input chips must have a clickable cross icon on the right.
Clicking the cross icon removes the chip selection from the input.

The chip should have an outline and no fill.
There should be no icon on the left.

The chip itself is not clickable.

## Filter chips

The filter chip is clickable and this toggles the chip between a selected and unselected state.

When unselected, the chip has an outline but no fill.
When selected, the chip has full or half tone fill, and has a tick mark on the left.

### Menu filter chips

...
