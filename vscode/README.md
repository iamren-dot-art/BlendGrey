# 💻 BlendGrey // VSCode System Configuration

This directory manages the core user experience properties for Visual Studio Code, transforming the environment into an optimized layout unified with your system-wide design aesthetic.

## 📝 Description & Workspace Features
Rather than running a standalone packaged marketplace extension, this theme is deployed via hyper-optimized `settings.json` injections. It crafts a complete workbench overlay designed around ultrawide screen workflows:
- **Ultrawide Centered Workspace:** Activates a pristine centered column layout, preventing neck strain by letterboxing code paths directly in your primary field of view.
- **Ruff Language Isolation:** Implements strict language-level scopes, isolating the lightning-fast Rust-based Ruff formatter to Python scripts while leaving HTML, CSS, and YAML configurations open for native system parsing.
- **Blender UI Emulation:** Maps outliner panel backgrounds, status bars, and document tab modules directly to your target Blender hex values.

## 💡 Inspiration
The visual design language is translated directly from the classic Blender workspace engine. The interactive token engine abandons flat dark theme styles, implementing highly reactive hover parameters (such as button-style inactive tabs that snap to pure white text on mouse-over) to create an intentional interface layout.

---

## 🛠️ Deployment Instructions

Since we are manually routing our custom layout overrides directly into the VS Code architecture, follow this breakdown to merge the theme elements cleanly into your cockpit setup:

1. **Grab the Raw Theme Blueprint:** Open the target theme `.json` file from this directory. 
2. **Copy the Token Highlights:** Locate the `tokenColors` array block. Copy the entire array. 
   - *Tip:* If you open this file inside VS Code, hover your cursor just to the left of the `tokenColors` line number and click the small disclosure arrow to collapse the block first. This lets you copy the entire array in one click so your scroll wheel doesn't melt.
3. **Access Your System Controls:** Open your global system configuration file. Hit `Ctrl + Shift + P` to fire up the Command Palette, type in `settings json`, and select **Preferences: Open User Settings (JSON)**.
4. **Deploy the TextMate Structural Rules:** Inside your root JSON object, create or locate the token customization block:
   ```json
   "editor.tokenColorCustomizations": {
       "textMateRules": []
   }
5. **Paste the Highlights:** Paste the `tokenColors` array you copied in Step 2 directly inside those empty `textMateRules: []` brackets.
6. **Capture the UI Shell:** Go back to our theme directory file, locate the `colors` object block, and copy the whole thing.
7. **Paint the Workbench Panels:** Return to your active `settings.json` file. Create a new line at the root level called `"workbench.colorCustomizations": {}` and paste that copied object directly inside the curly brackets.
8. **Lock in the Configuration:** Hit `CTRL + S` to save your updates. your workbench layout, side rails, text fonts, and button tabs will immediately flash and snap into your new unified layout.

## 📜 Application Changelog
### [0.1.0] - 2026-07-06
### Added

* Deployed unified workbench.colorCustomizations block aligning editor frames, sidebar headers, and activity bars to the matte-grey baseline.
* Configured custom text token overrides (editor.tokenColorCustomizations) implementing Coral Red structural keywords and Sky Blue function tags.
* Programmed independent tab.inactiveHoverBackground and text foreground markers to simulate live button tracking arrays.
* Structured hard wrapping limits (editor.wordWrapColumn: 120) paired with subtle vertical vertical guidelines for wide monitor displays.