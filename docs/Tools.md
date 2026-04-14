## Tools Preferences: Optimizing Your Workflow and Tools Panel

*Note: Looking for Tooltip settings? In newer versions of Photoshop, "Show Tooltips" and "Rich Tooltips" have been moved from this menu to **Edit > Preferences > Notifications**.*

- [ ] Enable Gestures
- [x] Use Shift Key for Tool Switch
- [x] Overscroll
- [ ] Enable Flick Panning
- [x] Double Click Layer Mask Launches Select and Mask Workspace
- [x] Vary Round Brush Hardness based on HUD vertical movement
- [x] Arrow Keys Rotate Brush Tip
- [x] Snap Vector Tools and Transforms to Pixel Grid
- [x] Show Reference Point when using Transform
- [x] Spring-loaded Tool Shortcuts
- [x] Zoom With Scroll Wheel (Optional)
- [ ] Animated Zoom (Personal Preference)
- [ ] Zoom Resizes Windows
- [ ] Zoom Clicked Point to Center

##### Under the Options Section

- [ ] **1. Uncheck "Enable Gestures"**
*(Optimizes settings for traditional mouse users)*

Touch control is very convenient when painting on touch displays. However, if you are using a traditional input device like a mouse, this setting is completely useless and can occasionally cause accidental canvas rotations. 

**Navigation:** `Edit > Preferences > Tools > Uncheck "Enable Gestures"`

- [x] **2. Check "Use Shift Key for Tool Switch"**
*(Prevents accidental tool changes)*

When checked, you must hold `Shift` while pressing a tool's shortcut key (like `M` for Marquee) to cycle through the hidden tools in that group (like switching from Rectangular to Elliptical Marquee). This prevents you from accidentally switching tools if you tap a key multiple times.

**Navigation:** `Edit > Preferences > Tools > Check "Use Shift Key for Tool Switch"`

- [x] **3. Check "Overscroll"**
*(Allows panning past the canvas edge)*

Overscroll allows you to use the Hand Tool to pan the image completely past the edge of the document window, so your canvas isn't locked to the center of the screen when zoomed out. This is highly recommended for unrestricted workspace navigation.

**Navigation:** `Edit > Preferences > Tools > Check "Overscroll"`

- [ ] **4. Uncheck "Enable Flick Panning"**
*(Stops the canvas from gliding automatically)*

What is flick panning in Photoshop? If you click with the hand tool, drag, and then release the mouse button while still in motion, the image continues to glide. While smooth, it requires extra OpenGL drawing resources from your GPU and can be annoying for precise work. Disable this to make the Hand Tool stop exactly when you release the mouse.

**Navigation:** `Edit > Preferences > Tools > Uncheck "Enable Flick Panning"`

- [x] **5. Check "Double Click Layer Mask Launches Select and Mask Workspace"**
*(Speeds up masking workflow)*

Checking this saves you a trip to the properties panel. Simply double-clicking a layer mask thumbnail will instantly open the powerful Select and Mask workspace for quick edge refinements.

**Navigation:** `Edit > Preferences > Tools > Check "Double Click Layer Mask..."`

- [x] **6. Check "Vary Round Brush Hardness based on HUD vertical movement" & "Arrow Keys Rotate Brush Tip"**
*(Improves brush control)*

These two settings give you advanced, rapid control over your brush tool. They allow you to change brush hardness by dragging up/down with the HUD color picker shortcut, and use your keyboard arrow keys to easily rotate the angle of directional brushes.

**Navigation:** `Edit > Preferences > Tools > Check both Brush settings`

- [x] **7. Check "Snap Vector Tools and Transforms to Pixel Grid"**
*(Prevents blurry edges on shapes)*

If you are a web or UI designer, this is a must. It ensures that when you draw vector shapes or transform them, their edges align perfectly with the pixel grid, preventing soft, anti-aliased, or blurry edges.

**Navigation:** `Edit > Preferences > Tools > Check "Snap Vector Tools..."`

- [x] **8. Check "Show Reference Point when using Transform"**
*(Brings back the center anchor point for precise scaling)*

Adobe hid the center target icon during Free Transform (`Ctrl + T`) by default in newer CC versions. Check this box to permanently bring back the reference point so you can easily change the pivot center for scaling and rotating.

**Navigation:** `Edit > Preferences > Tools > Check "Show Reference Point when using Transform"`

- [x] **9. Check "Spring-loaded Tool Shortcuts"**
*(Enables temporary tool switching)*

This is a massive workflow booster. If you hold down a tool's shortcut key (like holding `B` for Brush), use it, and then release the key, Photoshop will instantly "spring" back to the tool you were previously using. Leaving the sensitivity at the default 200 milliseconds works perfectly for most users.

**Navigation:** `Edit > Preferences > Tools > Check "Spring-loaded Tool Shortcuts"`

- [x] **10. Check "Zoom With Scroll Wheel" (Optional)**
*(Speeds up navigation for mouse users)*

If you want to know how to zoom in Photoshop with a mouse quickly, enable this. It allows you to instantly zoom in and out by rolling your mouse wheel, making navigating large canvases much faster.

**Navigation:** `Edit > Preferences > Tools > Check "Zoom With Scroll Wheel"`

- [ ] **11. Uncheck "Animated Zoom" (Personal Preference)**
*(Reduces GPU load for faster zooming)*

Animated Zoom provides a smooth transition when you click and hold the Zoom Tool. While it looks fluid, it relies entirely on your graphics card. If Photoshop is lagging, disable this to make Photoshop run faster with instant, "stepped" zooming.

**Navigation:** `Edit > Preferences > Tools > Uncheck "Animated Zoom"`

- [ ] **12. Uncheck "Zoom Resizes Windows" & "Zoom Clicked Point to Center"**
*(Keeps your workspace stable)*

"Zoom Resizes Windows" forces the actual document window to grow or shrink when you zoom, which constantly disrupts your workspace layout. "Zoom Clicked Point to Center" aggressively snaps whatever you click to the direct center of the screen, which can be disorienting. It is generally best to leave both unchecked.

**Navigation:** `Edit > Preferences > Tools > Uncheck both settings`
