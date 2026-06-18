# Midnight Capping

A reskinned and enhanced version of the Capping battleground timer addon for World of Warcraft, featuring a void/purple aesthetic and restored functionality.

## Features

### Click-to-Report Timer Bars
Timer bars are fully interactive again. Hold shift and click any active capture bar to instantly pre-fill a chat message alerting your team about an enemy capping a node. Uses Blizzard's `ChatFrame_OpenChat` method for full compatibility with the secure frame system.

### Minimap Button
A draggable minimap icon 

### Midnight Void Theme
Every element of the addon has been recolored to a cohesive void/purple palette:

- **Timer Bars** — Ethereal silver-purple for Alliance, bright void purple for Horde, deep purple for neutral objectives, and void black backgrounds
- **Options Panel** — All headings, labels, checkboxes, dropdowns, sliders, buttons (including Close), and tooltips use matching purple tones instead of the default yellow text and red buttons
- **Chat Output** — Addon messages print in purple for easy identification in busy chat windows
- **Title Branding** — The options panel header displays "Midnight Capping" in purple

### Slash Commands
- `/mcap` — Short alias

## Installation

Drop the `Capping` and `Capping_Options` folders into your `Interface/AddOns` directory. If upgrading from the original Capping addon, reset your profile (Options → Profiles → Reset) to pick up the new default colors.
