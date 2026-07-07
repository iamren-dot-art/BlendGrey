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

## 🛠️ Local Installation from Disk & Setup (Blender 5+)

Instead of using the basic installation installer, dropping the configuration file directly into Blender's system directory ensures it natively loads into your layout presets.

### Step 1: Locate Your OS Theme Directory
Navigate to the directory matching your machine's operating system. 

> 📂 *Note: If the `scripts`, `presets`, or `interface_theme` folders do not exist yet inside your version folder, simply right-click and create them manually.*

* **Windows:** `C:\Users\<YourUsername>\AppData\Roaming\Blender Foundation\Blender\5.x\scripts\presets\interface_theme\`
  *(Quick access: Press `Win + R`, type `%appdata%`, and navigate to `Blender Foundation\Blender\5.x\...`)*
* **macOS:** `/Users/<YourUsername>/Library/Application Support/Blender/5.x/scripts/presets/interface_theme/`
* **Linux:** `~/.config/blender/5.x/scripts/presets/interface_theme/`

### Step 2: Move the Theme File
Copy your downloaded `BlendGrey_[version].xml` file and paste it directly into that `interface_theme` directory.

### Step 3: Activate Inside Blender
1. **Fire up Blender** and navigate to the top menu bar: Select `Edit ➔ Preferences`.
2. Select the **Themes** tab on the left-hand sidebar.
3. Click the **Presets** dropdown menu at the very top of the page. Your newly copied `BlendGrey` layout will be sitting right there in the list. Select it to instantly skin the UI.

### Step 4: Configure the Typefaces
BlendGrey relies heavily on open-source NerdFonts to keep typography clean and legible on high-resolution displays. 
1. Download and install the dependencies from [Nerd Fonts](https://www.nerdfonts.com/font-downloads).
2. Inside Blender Preferences, select the **Interface** tab on the left sidebar.
3. Twirl down the **Text Rendering** section and apply the following targets:
    * **Interface font:** `JetBrainsMonoNL NFP Medium`
    * **Monospace font:** `Iosevka NFM`

### Step 5: The Finishing Tweak
Head down to the `Text Editor` options category inside the Themes menu. Double-check that your active syntax configurations mapped perfectly to our custom high-visibility pastel color values.

> 💡 **Pro-Tip:** If you ever need to manually adjust a stray hex color chip inside Blender's picker menus later, you don't need to click through sub-menus. Just hover your mouse pointer directly over any color box and hit `Ctrl + C` to copy or `Ctrl + V` to paste a hex string instantly!

---

## 📜 Application Changelog

## [1.0.0] - 2026-07-07

### Added
- Official v1.0.0 production baseline release for full compatibility with the Blender Extensions platform.
- Refactored `blender_manifest.toml` version metadata to meet registry requirements.

### Changed
- Promoted development tracking build state to stable release profile.
- Verified and synced internal theme XML architecture against Blender 5 theme parsing engines.

### [0.1.0] - 2026-07-06
#### Added
- Initial refactor of XML layout markers to ensure native parsing compatibility with the Blender 5 interface engine.
- Re-mapped `Syntax Reserved` (Coral `#ff7b72`), `Syntax Built-In` (Sky Blue `#79c0ff`), and `Syntax Special` (Warm Gold `#ffa657`) properties inside the Text Editor.
- Integrated crisp off-white defaults for basic syntax symbols and operators to break up uniform grey code strings.

#### Fixed
- Overmatched text lookup issues inside the Outliner and Properties hierarchies where generic labels were occasionally unreadable.