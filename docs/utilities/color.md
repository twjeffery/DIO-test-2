---
layout: default
title: Color
parent: Guidelines
nav_order: 4
---

# Color
{: .no_toc }

The colour palette is accessible and derived from the government brand standards.
There are three primary types of colour groups: layout, interactive, and status.

## On this page
{: .no_toc .text-delta }

1. TOC
{:toc}

---


## Layout
Grey and white should make up the majority of a website, with blue interspersed for contrast and visual interest. These layout colours are used for depth, hierarchy, and grouping.

Layout colours are derived from the GoA Corporate Identity colours.
<br>

| Colour  | Colour name   | Hex code | SCSS variable | Notes |
|:---------------|:---------------------|:-------------------------|:-------------------------|:-------------------------|
| ![#0081A2](../../assets/images/primary-blue.png) | Primary-blue | #0081A2 |  `$primary-blue` | Default brand colour. |
| ![#005072](../../assets/images/dark-blue.png)  | Dark-blue | #005072 | `$dark-blue` | Dark brand colour. |
| ![#C8EEFA](../../assets/images/light-blue.png)  | Light-blue | #C8EEFA | `$light-blue` | Light brand colour. |
| ![#333333](../../assets/images/black.png)  | Black | #333333 | `$black` | Text colour. |
| ![#FFFFFF](../../assets/images/white.png)  | White | #FFFFFF | `$white` | Text on primary buttons, dark backgrounds. |
<br>
![Colour do and don't](../../assets/images/colour-do-and-dont.png)
<br>
### Accessibility
{: .no_toc }
In accordance with WCAG 2.0 standards, in order to maintain a contrast ratio of 4.5 for all text sizes, the following rules apply:
1. All of the dark and primary colour backgrounds are accessible with white text.
2. All of the mid-tones and light colour backgrounds are accessible with dark text.
<br>
![Colour do and don't](../../assets/images/colour-do-dont-2.png)
<br>

## Interactive

Interactive colours are solely used for hyperlinks such as links and button elements. In the event that a dark background is used, however, the hyperlinks will be white.

Interactive colours are derived from tints of Alberta Blue.

| Colour  | Colour name   | Hex code | SCSS variable | Notes |
|:---------------|:---------------------|:-------------------------|:-------------------------|:-------------------------|
| ![#0070C4](../../assets/images/link.png) | Link | #0070C4 |  `$link` | Buttons and unvisited links. |
| ![#004F84](../../assets/images/hover.png) | Hover | #004F84 |  `$hover` | Button and link hover state. |

![Interactive do](../../assets/images/interactive-do-1.png)
![Interactive do](../../assets/images/interactive-do-2.png)
![Interactive don't](../../assets/images/interactive-dont-1.png)

<br>
### Accessibility
{: .no_toc }
Interactive colour text is accessible on white or light backgrounds In accordance with WCAG 2.0 standards, in order to maintain a contrast ratio of 4.5 for all text sizes.
<br>
## Grey

| Colour  | Colour name   | Hex code | SCSS variable | Notes |
|:---------------|:---------------------|:-------------------------|:-------------------------|:-------------------------|
| ![#666666](../../assets/images/dark-grey.png) | Dark-grey | #666666 |  `$dark-grey` | Secondary text. |
| ![#ADADAD](../../assets/images/grey.png) | Grey | #ADADAD |  `$grey` | Grey. |
| ![#DCDCDC](../../assets/images/mid-light-grey.png) | Mid-light-grey | #DCDCDC |  `$mid-light-grey` | Borders. |
| ![#F1F1F1](../../assets/images/light-grey.png) | Light-grey | #F1F1F1 |  `$light-grey` | Light background. |
<br>
## Status

There are four status colours, these colours are used exclusively for alert or callout boxes. Status colours are derived from official Provincial and Flag colours.

| Colour  | Colour name   | Hex code | SCSS variable | Notes |
|:---------------|:---------------------|:-------------------------|:-------------------------|:-------------------------|
| ![#005DAA](../../assets/images/status-info.png) | Status-info | #005DAA |  `$status-info` | Information status. |
| ![#00853F](../../assets/images/status-success.png) | Status-success | #00853F |  `$status-success` | Success status. |
| ![#FEBA35](../../assets/images/status-warning.png) | Status-warning | #FEBA35 |  `$status-warning` | Warning status. |
| ![#EC040B](../../assets/images/status-emergency.png) | Status-emergency | #EC040B |  `$status-emergency` | Emergency status. |
<br>

![Status do](../../assets/images/status-do-1.png)
![Status don't](../../assets/images/status-dont-1.png)


### Accessibility
{: .no_toc }
All text on status backgrounds with the exception of yellow must be white, in accordance with WCAG 2.0 standards, in order to maintain a contrast ratio of 4.5 for all text sizes.
