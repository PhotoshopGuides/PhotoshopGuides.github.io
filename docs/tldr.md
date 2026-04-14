# TL;DR: Performance-Only Optimization Guide

## General
- [ ] Uncheck "Auto show the home screen"
- [ ] Uncheck "Use Legacy 'New Document' Interface"
- [ ] Uncheck "Export Clipboard":
- [ ] Resize image during place. (Personal preference)

## Interface
1. Turn off Drop Shadows on Tabs and windows

        . Standard Screen Mode -> Border -> None
        . Full Screen with Menus -> Border -> None
        . Full Screen -> Border -> None
        . Artboard -> Border -> Line

## Workspace
- [x] Check "Auto-Collapse Iconic Panels"

## Notifications
- [x] Check "Enable Quiet Mode"

## Tools
- [ ] 1. Uncheck Show Tooltips (Optional)
- [ ] 2. Uncheck Show rich Tooltips
- [ ] 3. Uncheck Enable gestures
- [ ] 4. Uncheck Enable Flick Panning
- [x] 5. Check Show Reference point when using Transform.
- [x] 6. Check Zoom With Scroll Wheel (Optional)
- [ ] 7. Uncheck Animated Zoom. (Personal preference)

## History
- [ ] Uncheck "History Log"

## File Handling
- [ ] Image Previews -> Never Save:
- [ ] Maximize PSD/PSB Compatibility -> Never
- [x] Check "Save in Background"

## Export
- [x] Quick Export Format -> PNG/JPG

## Performance
##### Memory Usage - Ram - (Personal preference)

        . If Lower than 16gb ->  70%
        . If Lower than 32GB and don't run other programs with PS (Google Chrome) ->  80-90%
        . If More than 32 GB and run other programs with PS (Google Chrome) ->  75-80%

##### History & Cache - (Personal preference)
1. History State - (Personal preference)

        . Powerful system configuration and high storage
            If Master of Photoshop and don't use the Undo option Much - Less history state ≤ 50
            If Still a beginner and don't use Undo option a lot -  More history states≥ 50-70
        . Weak system configuration and less storage - Less history state ≤ 50

2. Cache Levels -

        . If work with small size images( ≤	2k pixels) - Cache Level - 2
        . If work with large size images( ≥	2k pixels) - Cache Level - 4-6

3. Cache Tile Size - 

        . Newer more powerful processors -> 128 K or 1024 K
        . Old less powerful processors -> 132 K or 1032 K

##### Legacy Compositing - 

Only if having problems and Blending modes don’t look right, or the color is weird.

## Image Processing
- [x] **Select Subject -> Device:** Forces the local GPU to process AI rather than the slow cloud.
- [x] **Selections/Remove Tool/Enhance -> Faster:** Prioritizes processing speed.

## Scratch Disks
- [x] **Primary Drive -> SSD/NVMe:** Never use an HDD.
- [x] **Failsafe:** Check a secondary internal drive to prevent "Scratch Disk Full" crashes.

## Cursors
- [x] **Painting Cursors -> Normal Brush Tip:** Simplest rendering for the GPU while painting.

## Transparency & Gamut
- [x] **Grid Size -> Medium:** Default is optimal; custom colors won't affect performance.

## Units & Rulers
- [x] **Units -> Pixels:** Standard for digital; no significant performance impact.

## Guides, Grid & Slices
- [ ] **Uncheck "Show Grid":** Hide when not in use to reduce UI rendering load.

## Plugins
- [ ] **Uncheck "Enable Generator":** Kills the background Node.js process (Major RAM saver).
- [ ] **Uncheck "Enable Remote Connections":** Closes network ports.

## Type
- [x] **Number of Recent Fonts -> 5:** Reduces font cache memory usage.
- [ ] **Font Preview Size -> None:** (In Type Menu) Essential for removing Type Tool lag.

## Technology Previews
- [ ] **Uncheck "Older GPU mode":** Do not use with modern cards.
- [x] **Check "Precise previews for 16-bit":** Ensures GPU handles 16-bit color correctly.


# Miscellaneous

**<a href="{{ '/Miscellaneous' | relative_url }}">Miscellaneous</a>**
