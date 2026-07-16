# BlendGrey

A color-neutral theme inspired by the iconic Blender 2.7 aesthetic. The theme utilizes a mid-grey foundation with deep slate accents and muted blue highlights. Reimagined for modern high-DPI workflows, it retains the signature matte surfaces and soft workspace transitions while introducing an updated UI and a pastel-toned syntax palette optimized for clarity and long-duration professional use.

## Contents 

[![Themes](https://img.shields.io/badge/Themes-4f699b)](#themes) [![Key Features](https://img.shields.io/badge/Key_Features-4f699b)](#key-features) [![Support](https://img.shields.io/badge/Support-4f699b)](#support) [![Credits & Acknowledgments](https://img.shields.io/badge/Credits_&_Acknowledgments-4f699b)](#credits--acknowledgments)
## Themes 

### 🧊 Blender 5+
A premium, low-chroma theme family designed to provide a distraction-free, professional workspace inspired by the classic Blender 2.7 aesthetic

<table>
  <thead>
    <tr>
      <th>Screenshots</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a target="_blank" rel="noopener noreferrer" href="./images/blender/BlendGrey_1.1.0_blender_5_sc_layout.png" alt="Layout" style="max-width: 100%;">
      </td>
      <td>
        <a target="_blank" rel="noopener noreferrer" href="./images/blender/BlendGrey_1.1.0_blender_5_sc_layout.png" alt="Layout" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>

<details>
#### Local Installation

1. Open the [latest releases page](#).
2. Download the BlendGrey zip file.
3. Extract the `BlendGrey.xml` file into the correct `interface_theme` directory for your system:

> **NOTE:** If the `scripts`, `presets`, or `interface_theme` directories do not yet exist inside your version folder, create them manually.

- **Windows:** `C:\Users\<YourUsername>\AppData\Roaming\Blender Foundation\Blender\5.x\scripts\presets\interface_theme\`
- **macOS:** `/Users/<YourUsername>/Library/Application Support/Blender/5.x/scripts/presets/interface_theme/`
- **Linux:** `~/.config/blender/5.x/scripts/presets/interface_theme/`

4. Launch Blender and navigate to the top menu bar: Select `Edit ➔ Preferences`.
5. Select the `Themes` tab on the left side of the window.
6. Select the `Presets` dropdown menu at the very top of the page. Your newly copied **BlendGrey** layout will be sitting right there in the list. Select it to instantly skin the UI.

> **Typography note:** BlendGrey relies heavily on **open-source NerdFonts** to keep typography clean and legible on high-resolution displays.

7. Download and install **JetBrains Mono** and **Iosevka NFM** from [NerdFonts](https://www.nerdfonts.com/font-downloads)
8. Select `Edit ➔ Preferences`, then `Interface`.
9. Expand the `Text Rendering` accordion arrow.
10. Set your fonts as Interface Font: `JetBrainsMonoNL NFP Medium`, Monospace Font: `Iosevka NFM`.
11. That's it! Your UI should now look just like the screenshots.


### 💻 VSCode

Complete workbench color theme and high-visibility text tokens.

![VSCode Theme](./images/vscode/BlendGrey_VSCode_v1.0.0.png)

> Installation instructions coming soon.
## Key Features

### Optimized neutral Viewport Workflow 
- **Unobtrusive UI:** By utilizing desaturated mid-greys and slate blues, the interface recedes into the background, allowing the vibrant colors of your 3D models, textures, and shaders to remain the primary focus without competition from the UI.
- **UX Perception:** Use of luminance shifts between panels creates a visual hierarchy, making it easy to distinguish between different groups of data and information quickly.

### Reduced Eye Strain & Visual Comfort
- **Low-Chroma Environment:** Minimizes optical fatigue by stripping away high-contrast colors common in many dark themes.
- **Soft Contrast Ratio:** The palette avoids harsh pure-black (#000000) and blinding white levels, opting for a balanced grey-scale that maintains legibility while reducing light emission/glare.

### High-Legibility Node & Code Systems
- **Pastel Syntax Palette:** Uses a carefully curated palette of pastel tones for development syntax and nodes. These colors are distinct enough to be easily identified but soft enough to prevent "color bleeding" or visual clutter in complex node trees.
- **Enhanced Node Readability:** The interface provides high-contrast text against muted backgrounds, ensuring that socket types, values, and labels remain sharp and readable even in dense, multi-layered node setups.

## Support

There might be a buried menu somewhere that is tough to read or an interactive button color that feels slightly off. If you run into any visual bugs or have ideas for layout tweaks, please let me know! This theme is actively maintained, and you can report issues or submit layout ideas as an [issue ticket on the project's GitHub](https://github.com/iamren-dot-art/BlendGrey/issues).

## Credits & Acknowledgments
- Initially forked from, and inspired by, the legacy *Grayscale* theme for Blender 4.2 LTS by [AlexMcKonst](https://github.com/AlexMcKonst/Grayscale-Color-Theme).
- Designed and maintained by **iamren**.
</details>