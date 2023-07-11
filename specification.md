---
title: Specification
---

# Overview

The design language should follow the [M3 material design specification](https://m3.material.io/) with the following exceptions.

# Chips

Use square chips from M2.

| M3 chip | Description |
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

# Filtering

## Filter chips

The filter chip is clickable and this toggles the chip between a selected and unselected state.

When unselected, the chip has an outline but no fill.
When selected, the chip has full or half tone fill, and has a tick mark on the left.

The state of a filter chip should not affect the state of another filter chip.

![Filter chip](./filter-chip.png "Filter chip")

## Menu filter chips

A menu filter chip has a downward triangular arrow on the right to indicate it is a menu filter chip.

When unselected, the chip has an outline but no fill.
When active, the chip has full or half tone fill, with a tick mark on the left and displaying the selected option. 

This solution should be used if there are more than three mutually exclusive options.

![Menu filter chip](./filter-menu-chip.png "Menu filter chip")

## Segmented buttons

Segmented buttons should not be used.

Instead a segmented filter chip should be used.

The solutions should be used if there are three of less mutually exclusive options.

![Segmented button](./segmented-button.png "Segmented button")
