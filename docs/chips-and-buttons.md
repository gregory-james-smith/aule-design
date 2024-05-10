---
title: Chips and buttons
---

# Chips and buttons

* Buttons
    * Press
    * Switch
    * Segmented switch
    * Coin
    * Icon
* Chips
    * Input
    * Filter
    * Assist
    * Suggestion

| Element | Guidance | Styling | Size |
|-|-|-|-|
| Buttons | Persistent and consistent | No outline, or gray outline, or full tone fill. Toned text. Upper case. Raised on focus. | Large |
| Chips | Dynamic and contextual | Gray outline or half tone fill. Gray text. Mixed case. Colour change on focus. | Small |

Table: Differences between chips and buttons

| Element | Form | ? |
|-|-|-|
| Press button |  |  |
| Switch button |  |  |
| Segmented switch button |  |  |
| Input cbip |  |  |
| Filter chip |  |  |
| Assist chip |  |  |
| Suggestion chip |  |  |

# Types of chips

| | Input | Choice | Filter | Action |
|-|-|-|-|-|
| Input | x |  |  |  |
| Filter |  | x | x |  |
| Assist |  |  |  | x |
| Suggestion |  |  |  | x |

Table: Comparison of M2 and M3 chips








# Chips

Use square chips from M3.
Chips either have no fill and an outline or half tone fill and no outline.






# Buttons

Use square button specification from M2.



# Switch / Choice / Select

These elements are used to .
For example filtering and querying search results.

|  | Number of options | Button | Chip | Field |
|-|-|-|-|-|
| Single select | 2-4 | Segmented button | Segmented chip |  |
| Single select | 3+ |  | Menu chip | Menu field |
| Multi select | 1-7 | Switch button | Filter chip |  |
| Multi select | 7+ |  |  | Input chip with ??? |

|  | Number of options | Switch | Form |
|-|-|-|-|
| Single select | 2-4 | Segmented switch | Segmented switch |
| Single select | 3+ | Menu switch | Menu field |
| Multi select | 1-7 | Switch | Switch |
| Multi select | 7+ | ??? | Input chip with ??? |

## Filter chips

<!-- Interaction -->
The filter chip is clickable and this toggles the chip between a selected and unselected state.

<!-- Options -->
Filter chips should be used for mutually exclusive options.
The state of a filter chip should therefore not affect the state of another filter chip.

<!-- Style -->
When unselected, the chip has an outline but no fill.
When selected, the chip has half tone fill, and has a tick mark on the left.

![Filter chip](./images/filter-chip.png "Filter chip")

## Menu chips

<!-- Interaction -->
The menu chip is clickable and this opens up a list of menu options.

<!-- Options -->
This solution should be used if there are more than three mutually exclusive options.

<!-- Style -->
A menu chip has a downward triangular arrow on the right to indicate it is a menu filter chip.
When unselected, the chip has an outline but no fill.
When active, the chip has half tone fill, with a tick mark on the left and displaying the selected option. 

![Menu chip](./images/menu-chip.png "Menu filter chip")

## Segmented chips

<!-- Interaction -->
Each option in the segmented chip is clickable and this toggles the chip between the different options.
One option is always selected and it will therefore have a default option.

<!-- Options -->
This solution should be used if there are two to three mutually exclusive options.

<!-- Style -->
The chip has an outline with each option segmented by a dividing line.
When an option is selected it has half tone fill, and has a tick mark on the left.

![Segmented button](./images/segmented-chip.png "Segmented button")

## Input chips

<!-- Options -->
Represent selections in a multiple selection input field.

<!-- Interaction -->
When editable, input chips must have a clickable cross icon on the right.
Clicking the cross icon removes the chip selection from the input.
The chip itself can be clickable, see M3 spec.

<!-- Style -->
The chip should have an outline and no fill.
The chip can have an optional icon on the left.

![Input chip](images/input-chip.png)

Action
======

| Button | Chip |
|-|-|
| Persistent and consistent | Dynamic and contextual |
| Button | Assist chip, Suggestion chip |

Table: Action chips and buttons

Suggestion chips
----------------

Suggestion chips present dynamically generated suggestions, such as possible quick-reply responses in a chat or starting a search query.

Suggestion chips have no fill and an outline with no icons.
The whole chip is clickable.
The chip displays the generated response or query question.

![Search query suggestions](images/query-suggestion-chip.png)

![Chat reply suggestions](images/chat-suggestion-chip.png)

Assist chips
------------

Assist chips represent smart or automated actions as though the user asked an assistant to complete the action.

Assist chips have no fill and an outline and should have an icon.
The whole chip is clickable.
Assist chips can show progress and confirmation feedback.

![Assist chips](images/assist-chip.png)

Action buttons
--------------

...
