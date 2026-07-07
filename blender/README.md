# 🧊 BlendGrey // Blender 5+

This directory houses the core workspace theme overrides for Blender. It features a complete overhaul of the 3D viewport canvas, UI layouts, and python scripting interface to capture a pristine, balanced workspace.

## 📝 Description & Workspace Features
The Blender configuration brings a unified dark matte interface design directly to your creative canvas. Key layouts include:
- **Core Viewport & Rails:** Utilizing a clean `#1d1d1d` base canvas flanked by crisp mid-grey menus to prevent eye strain during long modeling sessions.
- **Button-Style Tabs:** Re-engineered workspace navigation tabs to simulate distinct tactical modules, complete with clean white text on inactive states and bold black text when active.
- **Scripting Optimization:** High-visibility pastel syntax token mapping explicitly configured to separate language operations inside the text editor pane.

## 💡 Inspiration
This setup is built directly upon the legacy Grayscale theme by AlexMcKonst, refactored from the ground up to support modern Blender 5 data dictionaries. The syntax layout takes heavy cues from high-contrast engineering environments, moving away from muddy, dark default code tokens into punchy, identifiable pastels.

---

## 🛠️ Installation & Setup (Blender 5+)

Follow these quick steps to inject the `BlendGrey` template into your software profile:

1. **Fire up Blender** and navigate to the top menu bar: Select `Edit ➔ Preferences`.
2. Select the **Themes** tab on the left-hand sidebar of the preferences window.
3. Click the **Install...** button located in the upper-right corner of the panel.
4. Use the file browser to navigate to your WIP or local themes directory, select `BlendGrey_[version].xml`, and hit **Install Theme**.
5. **Set the tyupefaces:** BlendGrey makes use of OSS NerdFonts which are linked below. Goto `Edit ➔ Preferences`, select the `Interface` tab, then twirl down the `Text Rendering` section.
    * **Interface font:** [JetBrainsMonoNL NFP Medium](https://www.nerdfonts.com/font-downloads)
    * **Monospace font:** [Iosevka NFM](https://www.nerdfonts.com/font-downloads)
6. **The Finishing Tweak:** Head to the `Text Editor` dropdown inside that same Themes menu. Ensure your syntax colors match the high-contrast pastel configurations. 

> 💡 **Pro-Tip:** If you ever need to manually adjust a stray hex color chip inside Blender's picker menus later, you don't need to click through sub-menus. Just hover your mouse pointer directly over any color box and hit `Ctrl + C` to copy or `Ctrl + V` to paste a hex string instantly!

---

## 📜 Application Changelog

### [0.1.0] - 2026-07-06
#### Added
- Initial refactor of XML layout markers to ensure native parsing compatibility with the Blender 5 interface engine.
- Re-mapped `Syntax Reserved` (Coral `#ff7b72`), `Syntax Built-In` (Sky Blue `#79c0ff`), and `Syntax Special` (Warm Gold `#ffa657`) properties inside the Text Editor.
- Integrated crisp off-white defaults for basic syntax symbols and operators to break up uniform grey code strings.

#### Fixed
- Overmatched text lookup issues inside the Outliner and Properties hierarchies where generic labels were occasionally unreadable.