CRAFT - Timeline Assist
=======================

CRAFT - Timeline Assist is a lightweight timeline workflow tool for 3ds Max animators who need faster control over long animation ranges. It replaces timeline hunting with a clean dark interface for focusing frame ranges, creating animation section presets, and jumping between saved timing blocks instantly.

Key highlights:

- Quickly zoom, pan, and resize focused timeline ranges.

- Save animation sections like walk cycles, jumps, attacks, shots, or timing passes as preset bars.

- Click any preset to instantly focus the timeline to that exact frame range.

- Create presets from the current range or from selected keyframes.

- Presets are stored inside the Max scene, so each file keeps its own animation layout.

- Clean one-row preset panel by default, with expandable rows when needed.

- Startup toggle, color options, hide presets toggle, and right-click preset editing.

- Designed as part of the CRAFT Toolset with a minimal dark UI that feels native to 3ds Max.

In short: CRAFT - Timeline Assist helps animators organize, navigate, and reuse timeline ranges faster, especially in scenes with multiple animations living inside one long timeline.
Files you need:


Release Notes:

v1.04
- Fixed the startup listener warning caused by redundant preset scrollbar signal disconnects.
- Preset scrollbar setup now connects cleanly once and avoids noisy RuntimeWarning messages on startup.

v1.03
• Added numbered preset rows.
• Reserved the row-number lane so preset bars do not overlap row labels.
• Added row-snapped scrollbar and wheel scrolling in the preset panel.
• Changed preset panel zoom to Alt + mouse wheel.
• Improved Alt-wheel handling for 3ds Max embedded Qt.
• Double-clicking an empty preset row now tries to create the preset on that row first, then falls back to another available
row if needed.

v1.02
• Added multi-select for preset bars.
• Added installer cleanup improvements and updated help/support information.



Installation:

1. Open Autodesk 3ds Max 2027.
2. Drag CRAFT - Timeline Assist.mzp into the 3ds Max viewport.
3. Choose Install in the CRAFT - Timeline Assist popup.
4. Launch from CRAFT > CRAFT - Timeline Assist.

Shortcut:

Assign a keyboard shortcut to:

Category: CRAFT
Action: CRAFT - Timeline Assist

Running this shortcut opens the tool again if the user closed it.

Uninstall:

Drag CRAFT - Timeline Assist.mzp into the viewport and choose Uninstall, or after installation use:

CRAFT > Uninstall Timeline Assist

The uninstall macro removes the startup launcher, installed runtime files, callbacks, and CRAFT Timeline Assist macros.

Notes:

- Startup is enabled by default after install.
- GitHub: https://github.com/TheTreeHouseof95/CRAFT---Timeline-Assist.git
- For bugs/requests visit: https://github.com/TheTreeHouseof95/CRAFT---Timeline-Assist/discussions
- Email: thetreehouseof95@gmail.com
