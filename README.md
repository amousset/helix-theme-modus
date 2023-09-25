# Modus themes for Helix

Adaption of the great Emacs [Modus themes](https://protesilaos.com/emacs/modus-themes)
for the Helix editor.

## Goals

* Follow the core principles of the original themes:
  * Legibility
  * Accessibility

* Stay visually close to its defaults
  * Re-use the color palette as much as possible

## Non-goals

* Reproduce the theme exactly
  * Helix is a (very) different context
  * It is impossible anyway!

## Differences with original theme

The Helix context imposes several strict constraints:

* Low configurability
  * _Helix is as radical as Emacs, but in an opposite direction_
  * The themes are very simple and cannot include logic
* Terminal UI
  * Limits the typographic abilities
  * Requires special effort to show the difference between code and UI

* For floating windows, we need a clean separation with the background:
  * For big centered windows we can keep the main bg
  * For smaller windows (popups) we need a different background

* Center on content, the interface should get out of the way

## Screenshots

TODO

## Installation

This theme requires a terminal with true color support.

```shell
cp *.toml ~/.config/helix/runtime/themes/
```
