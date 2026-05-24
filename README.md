# Minefun.io Display Enhancer

A draggable, live filter panel that enhances the visual display of the game canvas on **minefun.io**.  
Built as a Tampermonkey userscript.

Press `Ctrl + Alt` to toggle the panel.  
Works on `minefun.io` and all its subdomains.

---

## Features

- Real‑time application of CSS filters and overlays directly on the game canvas.
- Adjustable sliders for brightness, contrast, saturation, hue, blur, sepia, invert, gamma, temperature.
- Screen effects: vignette and scanlines.
- Quick presets with a single click: Night Mode, Grayscale, High Contrast, Film Noir, Vivid, Retro, VHS Glitch, CRT Monitor.
- Active preset indication – click again to reset all filters.
- Toast notifications when presets are applied or filters reset.
- Draggable and resizable panel.
- All settings saved automatically in `localStorage` and restored across sessions.
- Rainbow accent color on slider tracks for visual appeal.
- Built‑in info tab with keyboard shortcut and Discord link.
- No external dependencies – pure vanilla JavaScript.

---

## Installation

1. Install a userscript manager like **Tampermonkey**, **Greasemonkey**, or **Violentmonkey**.
2. Create a new script and paste the full source code.
3. Save – it will run automatically on `minefun.io` and its subdomains.

---

## Usage

1. Press `Ctrl + Alt` to show the Display Enhancer panel.
2. Use the tabs to navigate between **Display**, **Color**, **Effects**, **Presets**, and **Info**.
3. Adjust any slider – the filter is applied instantly to the game canvas.
4. Click a **preset** button to quickly apply a predefined look; click the same preset again to reset all.
5. Press the **RESET ALL** button at the bottom to revert to default values.
6. Drag the panel by its header bar, and resize from the corner.

Filters are applied only to the game canvas (automatically detected and re‑detected when a new match starts).

---

## Keyboard Shortcut

| Shortcut       | Action          |
|----------------|-----------------|
| `Ctrl + Alt`   | Toggle panel    |

---

## Presets

| Preset         | What it does                                       |
|----------------|----------------------------------------------------|
| Night Mode     | Reduces brightness, warms colours, lowers saturation |
| Grayscale      | Removes all colour (saturation 0)                  |
| High Contrast  | Increases contrast and brightness, vivid look      |
| Film Noir      | Black & white with high contrast and sepia tint    |
| Vivid          | Super‑saturated and bright                         |
| Retro          | Sepia tone and warm hue shift                      |
| VHS Glitch     | Scanlines, vignette, slight blur and colour shift  |
| CRT Monitor    | Scanlines, vignette, high contrast, slight blur    |

---

## Customization

Settings are stored in `localStorage` under the key `mf_display_settings`.  
You can modify the default values or the preset definitions directly in the script.

---

## Author

**Itz_Krishna AKA Everlasting**

---

**Short Description:** Adjustable game display filter enhancer.
